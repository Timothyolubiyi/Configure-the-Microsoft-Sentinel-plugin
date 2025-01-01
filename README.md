# Configure-the-Microsoft-Sentinel-plugin
In this exercise, you configure the Microsoft Sentinel plugin and run some test prompts to confirm that Copilot is using the plugin.
Task: Test a Microsoft Sentinel prompt
When working with technology, it's not uncommon to try use a feature and then realize, after some trouble-shooting, that you forgot to enable that feature. In this first task, you test a Microsoft Sentinel prompt with the Microsoft Sentinel plugin disabled. You go through this task so that you can get exposure to the information provided in the process log that helps you troubleshoot the issue.

1. Open the simulated environment by selecting this link: Microsoft Security Copilot. USE THE Simulation LAB   https://7lraebk5le-bwf0w8xmf1.app.highlights.guide/

2. From the prompt bar, enter the prompt Summarize the Microsoft Sentinel incident 30342. You can copy and paste the prompt into prompt bar. Then select the run icon.

3. The Copilot process log shows that it can't complete your request. Expand the items in the process log for more detailed information.

**Continue; Configure and enable the Microsoft Sentinel plugin**

In this task, you'll configure the Sentinel plugin. To do this, you need to access the Azure portal to obtain the necessary information.

1. From prompt bar, select the sources icon sources icon.

2. From the manage sources page, expand the view for the Microsoft plugins by **selecting Show 11 more and scroll down until Microsoft Sentinel** is visible.

3. Select the **Set up** button and note the parameters that need to be configured. Select the information icon next to any of the parameters. Keep this browser tab open, you'll come back to this page for each parameter to be configured.


4. Use your right mouse key to open the link to the Azure portal in a new tab or window: https://m97x28eyav-oskrm35d7l.app.highlights.guide/#home Azure portal.
 It's important that access to the Azure portal and access to Security Copilot be available as separate browser tabs, as you'll be accessing both tabs for this task.

A.-  Select Log Analytics workspaces, it should be displayed as an icon under Azure services.
B. - Select the workspace associated with your Sentinel deployment. For this exercise, select **Woodgrove-LogAnalyticsWorkspace**.
C. - You should be on the overview page, if not select it now. From here you copy the information required to configure the Sentinel plugin.
D. - Recall that the first parameter listed on the Microsoft Sentinel settings page is the Default workspace name. Hover over the workspace name, until the clipboard icon is displayed. Select Copy to clipboard.
E. - Keep this browser tab open as you'll be referring to the information on this page for each parameter to be configured.

5. - Switch back to the Copilot browser tab. Place your mouse cursor in the workspace name field and right-click to paste the contents of the clipboard to the clipboard. The workspace name is added to the field.

6. - Repeat the steps until you have configured the remaining two fields. Once all the fields are populated, select Save.

7. - Make sure the toggle switch for the **Sentinel plugin is enabled**, then close the manage sources window by selecting the X.

**Task: Retest the Microsoft Sentinel prompt**
Now that the Sentinel plugin is enabled, you'll run the prompt you tried earlier. With the prompt successfully executed, you'll save the prompt to the pin board and get a link to the session so you can share it with a colleague.

1.  Once you've configured the plugin, you need to create a new session to rerun the Sentinel prompt. From the top of the page, select Microsoft Security Copilot.

2.  In the prompt bar, enter the prompt **Summarize the Microsoft Sentinel incident 30342**. You can copy and paste the prompt into the prompt bar. Then select the run icon.

3.  The Copilot process log shows that the prompt executed successfully by displaying green check marks.

4. Select the box icon next to the pin icon to select the response. Selecting the the Pin icon pin icon pins the response to the pin board, which automatically opens. The pin board shows a summary for the pined responses.

In this exercise, you ran a prompt that requires the Microsoft Sentinel plugin to be enabled. The first time you ran the prompt, Copilot wasn't able to complete the request. The process log provided the information to help you troubleshoot the issue. You then configured and enabled the plugin. With the plugin enabled you were able successfully run the prompt.
