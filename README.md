# lucybobeck
var badges = $.treehouseBadges(teacosy);

$(badges).each(function() {
    $('#my_element').append(this.img);
});
