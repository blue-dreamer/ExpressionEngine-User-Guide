<!--
    This source file is part of the open source project
    ExpressionEngine User Guide (https://github.com/ExpressionEngine/ExpressionEngine-User-Guide)

    @link      https://expressionengine.com/
    @copyright Copyright (c) 2003-2020, Packet Tide, LLC (https://www.packettide.com)
    @license   https://expressionengine.com/license Licensed under Apache License, Version 2.0
-->

# ExpressionEngine v6 Change Log
## Version 6.0.2 (Release: January 27, 2021)
- **Bug Fixes** 💃🐛 
  - Resolved [#192](https://github.com/ExpressionEngine/ExpressionEngine/issues/192) where keywords filter was not always working in Entries Manager when using Safari browser.
  - Resolved [#812](https://github.com/ExpressionEngine/ExpressionEngine/issues/812) where SuperAdmin could not log in after editing its role.
  - Resolved [#817](https://github.com/ExpressionEngine/ExpressionEngine/issues/817) where it was not possible to add new items in Simple Commerce.
  - Resolved a bug where no icons where displaying for missing files in file field.
  - Resolved display issues in file browser for files that have been physically deleted.

- **Enhancements** 🚀
  - Added extension hooks for Role Model

## Version 6.0.1 (Release: January 22, 2021)
- **Bug Fixes** 💃🐛 
  - Resolved [#783](https://github.com/ExpressionEngine/ExpressionEngine/issues/783) where an exception could be thrown when deleting users with long user names.
  - Resolved [#768](https://github.com/ExpressionEngine/ExpressionEngine/issues/768) where some buttons on the "forgot password" screen where not translated.
  - Resolved [#730](https://github.com/ExpressionEngine/ExpressionEngine/issues/730) where a link was invalid.
  - Resolved [#744](https://github.com/ExpressionEngine/ExpressionEngine/issues/744) where the incorrect file upload directory was selected in an RTE field.
  - Resolved [#733](https://github.com/ExpressionEngine/ExpressionEngine/issues/733) where jump menu was not changing correctly when a user choose a different language for the Control Panel.
  - Resolved [#753](https://github.com/ExpressionEngine/ExpressionEngine/issues/753) where debug was set to automatically set to `1` on new install.
  - Resolved [#737](https://github.com/ExpressionEngine/ExpressionEngine/issues/737) where images uploaded to a file grid field did not always show as added to the entry.
  - Resolved [#713](https://github.com/ExpressionEngine/ExpressionEngine/issues/713) where site was set to "offline" after upgrading to EE6.
  - Resolved [#693](https://github.com/ExpressionEngine/ExpressionEngine/issues/693) where only 5 images were added to an entry when adding more than 5 images to a file grid within a fluid field.
  - Resolved [#735](https://github.com/ExpressionEngine/ExpressionEngine/issues/735) where installer could not finish on some shared hosting environments.
  - Resolved [#740](https://github.com/ExpressionEngine/ExpressionEngine/issues/740) where on-the-fly manipulations were not updated when an image is replaced.
  - Resolved [#714](https://github.com/ExpressionEngine/ExpressionEngine/issues/714) where Color Picker events are not fired on Grid settings page
  - Resolved [#742](https://github.com/ExpressionEngine/ExpressionEngine/issues/742) where `logged_in_primary_role_id` was not parsing in templates.
  - Resolved [#725](https://github.com/ExpressionEngine/ExpressionEngine/issues/725) where a language key was missing for the Jump Menu.
  - Resolved [#721](https://github.com/ExpressionEngine/ExpressionEngine/issues/721) where channels named with numbers where not shown correctly in main navigation.
  - Resolved [#708](https://github.com/ExpressionEngine/ExpressionEngine/issues/708) where MySQL's join limit could be reached and cause errors.
  - Resolved [#717](https://github.com/ExpressionEngine/ExpressionEngine/issues/717) where new user roles where not being shown in the main navigation.
  - Resolved [#572](https://github.com/ExpressionEngine/ExpressionEngine/issues/572) where the main navigation flyout menu could not accommodate long list of channels.
  - Resolved [#696](https://github.com/ExpressionEngine/ExpressionEngine/issues/696) where the EECLI was not installed via 1-Click update.
  - Resolved [#703](https://github.com/ExpressionEngine/ExpressionEngine/issues/703) where channel form could not upload files to other site.
  - Resolved [#691](https://github.com/ExpressionEngine/ExpressionEngine/issues/691) where add-on classes were not properly aliased.
  - Resolved [#705](https://github.com/ExpressionEngine/ExpressionEngine/issues/705) where an incorrect tag was added to docs.

- **Enhancements** 🚀
  - EE Core code is now formatted for PSR-12!
  - Select buttons in Relationship fields can now be customized.
  - Add cache clearing option for the JumpMenu [#623](https://github.com/ExpressionEngine/ExpressionEngine/issues/623)
  - Removed Channel options in relationship field when there is only one channel to choose from [#684](https://github.com/ExpressionEngine/ExpressionEngine/issues/684).
  - Added more heading options to the RTE field [#695](https://github.com/ExpressionEngine/ExpressionEngine/issues/695).

## Version 6.0.0 (Release: December 17, 2020)
- **New Control Panel Design** 🎨
  - Added Jump Menu. Navigate ExpressionEngine fast
  - Many new changes and improvements that make the control panel cleaner, and more delightful to use
  - Brand new dark theme.
  - New sidebar navigation
  - New Account Menu
  - Create and Edit navigation items have been merged
  - Better navigation. Navigation buttons are now in a more consistent location. The member account menu shows the member's primary role. "Manager" has been removed from most of the page names, e.g "Entry Manager" is now - "Entries". Navigation works better on mobile.
  - Add-ons and categories have been moved out of the dev menu and into the sidebar
  - The files page has a new thumbnail view
  - Collapsible sidebar navigation
  - Editing and preview files is now easier in the files manager
  - “Sticky entries” is now optional feature that can be turned on in preferences for each channel
  - You can now drag to change the width of the live preview panes
  - The add-ons page uses a new card view, shows add-on icons, and has a separate tab for updates
  - The SQL query form has new buttons to insert common used SQL snippets
  - The tabs and save buttons on the edit entry page are now sticky
  - The date picker has a new today button, and days are easier to click.
  - The grid field now collapses on mobile
  - The dashboard has been upgraded to be more useful.
  - "Remove" wording has been changed to the more appropriate "delete" for destructive actions.
  - Deletion confirm dialogs are more scary
  - Pagination improvements. Pagination shows 8 pages, instead of 3.
  - You can now tab to toggle buttons
  - Added support for third-party add-on icons to Add-on Manager
  - Changed sidebar copyright company name
  - Default avatars have been removed
  - UX Updates to encourage CMS integrators to take the appropriate next steps while using the CMS
  - And many more changes!
  - Template editor improvements
    - You can now comment EE code with command + / in the template editor
    - You can now select a single line of text when clicking on a gutter number in the template editor
    - Improved EE syntax highlighting
  - New Member Template examples have been added
  - New entry manager (Entries listing page) with filters bar, better layout, simpler search, and individual filter clearing!
  - Live preview has been modified to make add-on support easier
  - New Variable modifiers to crop, resize, and rotate images
  - Member Groups have been replaced with member roles.
    - Members have one primary roles, and can also can have multiple other roles
    - Role permissions are additive
  - New Field Types
    - New RTE
    - New Color Picker Field
    - New Relationship field
  - Began working toward ADA compliance
  - Users can now upload [WebP](https://developers.google.com/speed/webp) images via the File Manager [#304](https://github.com/ExpressionEngine/ExpressionEngine/issues/304)
  - The Blacklist/Whitelist Module for ExpressionEngine has been renamed to Block and Allow Module.
  - Upload Directory and Upload Path are now populated with `{base_url}` and `{base_path}` by default when creating new Upload Directories.
  - The success notification for a saved entry now links back to the saved entry.
  - Improved error message for removed models and tables.
  - Updated default system error messages to use new v6 design.
  - Updated styles for 1-Click Updater and Installer Screens



- **Bug Fixes** 💃🐛 
  - Resolved bugs in the updaters where MySQL errors could be triggered.
  - Fixed Live Preview functionality with Grid and Fluid Fields
  - Fixed a bug where the debugger code highlighter would also highlight and overwrite other code blocks on a site's page
  - Resolved issue where new template groups were not recognized on a blank install until the user also creates a new template group in the Template Manager.
  - Resolved [#431](https://github.com/ExpressionEngine/ExpressionEngine/issues/431) where the EE Block/Allow list was not able to be downloaded from within the Block/Allow Module.
    

- **Developers** 💻
  - Moved tests to use [Cypress](https://www.cypress.io/)
  - Add-ons that use Members must use Roles in place of MemberGroups
  - Removed EllisLab from Namespace and EllisLab folders
  - Updated CodeMirror to version 5.48
  - Deprecated the Channel Status controller `getForegroundColor()`
  - The member property `display_avatars` has been removed
  - The config options `enable_avatars` and `allow_avatar_uploads` have been removed
  - Removed the deprecated jQuery add-on
  - Removed the deprecated Emoticon add-on
  - Forgot Password emails will now respect your "Mail Format" preference (essentially enabling the ability to use - HTML in Forgot Password emails).
  - Fixed a bug where table bulk selections can be saved by the browser on page reload, but don't show in the UI.
  - New base classes can be extended as part of add-ons (setting the stage for future functionality (migrations etc.- )  Not a required change to add-ons but encouraged. 
  - [`allow_php` config override](general/system-configuration-overrides.md#allow_php) now needs to be set in config.php to be able to enable [PHP in templates](templates/overview.md#php-in-templates).
  - `upload_file_name_blacklist` config override renamed to `upload_blocked_file_names`
  - `exp_sites.site_pages` data type has been changed to MEDIUMTEXT.
  - Moved language files from `system/ee/legacy` folder to `system/ee/language`.
  - Added `$config['legacy_member_templates'] = 'y';` to allow legacy member functionality which is now not allowed by default [see System Config Overrides](general/system-configuration-overrides.md#legacy_member_templates).    
  - New member groups no longer have access to HTTP-protected templates by default [#279](https://github.com/ExpressionEngine/ExpressionEngine/issues/279).