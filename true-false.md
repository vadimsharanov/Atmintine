this.DOM = document.querySelector(this.selector);

if (this.DOM) {
    return true;
} else {
    return false;
}

return this.DOM ? true : false;

return !!this.DOM;