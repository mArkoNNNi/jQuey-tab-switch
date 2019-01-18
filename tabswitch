<script>
 jQuery(document).ready(function ($) {
 $('div[id^="d_tab"]').click(function () {
 $(this).removeClass('notactivetab').siblings().addClass('notactivetab');
 });
 $('div[id^="d_tab"]').click(function () {
    var number = this.id.replace(/[^0-9]/g, '');
    var divId = "cont" + number;  
    $("#" + divId).removeClass('deactivated').addClass('activated').siblings().removeClass('activated').addClass('deactivated');
});

});
</script>
