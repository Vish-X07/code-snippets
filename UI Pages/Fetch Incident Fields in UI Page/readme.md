Fetch Incident fields(or any table fields) in a UI page via UI Action trigger

Steps

- Create a UI action and create a function.
- Add the UI action script provided in the Script section.
- This code helps to render a pop up window of 600x600 dimentions for the UI page and passes the current sys id to UI page.
- Make sure to add the code in the UI Page : <g:evaluate var="jvar_sysId" expression="RP.getWindowProperties().get('sysparm_sys_id')" />
- Create a UI Page and add the HTML Code provided.
- Trigger the UI Action from the Incident form and it should render the ui page with the incident fields data.
- Add additional static or dynamic data as per the requirement.
