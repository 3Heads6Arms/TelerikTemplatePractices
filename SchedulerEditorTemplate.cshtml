@using Calendar.Web.Models
@model AppointmentViewModel
@{
    ViewContext.FormContext = new FormContext();
}

@functions{
    public Dictionary<string, object> generateDatePickerAttributes(
           string elementId,
           string fieldName,
           string dataBindAttribute,
           Dictionary<string, object> additionalAttributes = null)
    {

        Dictionary<string, object> datePickerAttributes = additionalAttributes != null ? new Dictionary<string, object>(additionalAttributes) : new Dictionary<string, object>();

        datePickerAttributes["id"] = elementId;
        datePickerAttributes["name"] = fieldName;
        datePickerAttributes["data-bind"] = dataBindAttribute;
        datePickerAttributes["required"] = "required";
        datePickerAttributes["style"] = "z-index: inherit;";

        return datePickerAttributes;
    }
}

<div class="k-edit-label">
    @Html.LabelFor(x => x.Title)
</div>
<div data-container-for="title" class="k-edit-field">
    @Html.TextBoxFor(x => x.Title)
</div>
<div class="k-edit-label">
    @Html.LabelFor(x => x.Start)
</div>
<div data-container-for="start" class="k-edit-field">
    @(Html.Kendo().DateTimePickerFor(model => model.Start)
        .HtmlAttributes(generateDatePickerAttributes("startDateTime", "start", "value:start,invisible:isAllDay")))

    @(Html.Kendo().DatePickerFor(model => model.Start)
        .HtmlAttributes(generateDatePickerAttributes("startDate", "start", "value:start,visible:isAllDay")))

    <span data-bind="text: startTimezone"></span>
    <span data-for="start" class="k-invalid-msg"></span>
</div>
<div class="k-edit-label">
    @(Html.LabelFor(model => model.End))
</div>
<div data-container-for="end" class="k-edit-field">

    @(Html.Kendo().DateTimePickerFor(model => model.End)
        .HtmlAttributes(generateDatePickerAttributes(
            "endDateTime",
            "end",
            "value:end,invisible:isAllDay",
            new Dictionary<string, object>() { { "data-dateCompare-msg", "End date should be greater than or equal to the start date" } })))

    @(Html.Kendo().DatePickerFor(model => model.End)
        .HtmlAttributes(generateDatePickerAttributes(
            "endDate",
            "end",
            "value:end,visible:isAllDay",
            new Dictionary<string, object>() { { "data-dateCompare-msg", "End date should be greater than or equal to the start date" } })))

    <span data-bind="text: endTimezone"></span>
    <span data-for="end" class="k-invalid-msg"></span>
</div>
<div class="k-edit-label">
    @Html.LabelFor(x => x.IsAllDay, "All day event")
</div>
<div data-container-for="isAllDay" class="k-edit-field">
    <input data-bind="checked: isAllDay" data-val="true" id="IsAllDay" name="IsAllDay" type="checkbox" />
</div>

<div class="k-edit-label">
    <label for="timezone"> </label>
</div>
<div data-container-for="timezone" class="k-edit-field">
    @Html.Kendo().Button().Name("btnTimeZone").Tag("a").Content("Time zone").HtmlAttributes(new { data_bind = "invisible:isAllDay" })
</div>
<div class="k-popup-edit-form k-scheduler-edit-form k-scheduler-timezones" style="display:none">
    <div class="k-edit-form-container">
        <div class="k-edit-label"></div>
        <div class="k-edit-field">
            <label class="k-check">
                <input class="k-timezone-toggle" type="checkbox">Use separate start and end time zones
            </label>
        </div>
        <div class="k-edit-label">
            <label for="startTimezone">Start timezone</label>
        </div>
        <div data-container-for="startTimezone" class="k-edit-field">
            <div data-bind="value:startTimezone" name="startTimezone" data-role="timezoneeditor" style="display: block;"><span title="" class="k-widget k-dropdown k-header" unselectable="on" role="listbox" aria-haspopup="true" aria-expanded="false" tabindex="0" aria-owns="6aa0a177-973e-4e58-8453-3e99ed3d3d3e_listbox" aria-disabled="false" aria-readonly="false" aria-busy="false"><span unselectable="on" class="k-dropdown-wrap k-state-default"><span unselectable="on" class="k-input">No timezone</span><span unselectable="on" class="k-select"><span unselectable="on" class="k-icon k-i-arrow-s">select</span></span></span><input id="6aa0a177-973e-4e58-8453-3e99ed3d3d3e" data-role="dropdownlist" style="display: none;"></span><span title="" class="k-widget k-dropdown k-header" unselectable="on" role="listbox" aria-haspopup="true" aria-expanded="false" aria-owns="" aria-disabled="true" aria-readonly="false" style="display: none;"><span unselectable="on" class="k-dropdown-wrap k-state-disabled"><span unselectable="on" class="k-input"></span><span unselectable="on" class="k-select"><span unselectable="on" class="k-icon k-i-arrow-s">select</span></span></span><input data-role="dropdownlist" disabled="disabled" style="display: none;"></span></div>
        </div>
        <div class="k-edit-label"><label for="endTimezone">End timezone</label></div>
        <div data-container-for="endTimezone" class="k-edit-field">
            <div data-bind="value:endTimezone" name="endTimezone" data-role="timezoneeditor" style="display: block;"><span title="" class="k-widget k-dropdown k-header" unselectable="on" role="listbox" aria-haspopup="true" aria-expanded="false" tabindex="0" aria-owns="05486094-12fa-4586-8c48-c87d167c360b_listbox" aria-disabled="false" aria-readonly="false" aria-busy="false"><span unselectable="on" class="k-dropdown-wrap k-state-default"><span unselectable="on" class="k-input">No timezone</span><span unselectable="on" class="k-select"><span unselectable="on" class="k-icon k-i-arrow-s">select</span></span></span><input id="05486094-12fa-4586-8c48-c87d167c360b" data-role="dropdownlist" style="display: none;"></span><span title="" class="k-widget k-dropdown k-header" unselectable="on" role="listbox" aria-haspopup="true" aria-expanded="false" aria-owns="" aria-disabled="true" aria-readonly="false" style="display: none;"><span unselectable="on" class="k-dropdown-wrap k-state-disabled"><span unselectable="on" class="k-input"></span><span unselectable="on" class="k-select"><span unselectable="on" class="k-icon k-i-arrow-s">select</span></span></span><input data-role="dropdownlist" disabled="disabled" style="display: none;"></span></div>
        </div>
        <div class="k-edit-buttons k-state-default"><a class="k-button k-scheduler-savetimezone" href="#">Save</a><a class="k-button k-scheduler-canceltimezone" href="#">Cancel</a></div>
    </div>
</div>
<div class="k-edit-label">
    @Html.LabelFor(x => x.RecurrenceRule, "Repeat")
</div>
<div data-container-for="recurrenceRule" class="k-edit-field">
    @(Html.Kendo().RecurrenceEditorFor(model => model.RecurrenceRule)
        .HtmlAttributes(new { data_bind = "value:recurrenceRule" }))
</div>
<div class="k-recur-view"></div>
<div class="k-edit-label">
    @Html.LabelFor(x => x.Description)
</div>
<div data-container-for="description" class="k-edit-field">
    @(Html.TextAreaFor(model => model.Description, new { @class = "k-textbox", data_bind = "value:description" }))
</div>

@{
    ViewContext.FormContext = null;
}
