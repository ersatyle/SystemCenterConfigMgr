`Win 10 1607.zip` - Legacy OSD TS designed to be used with a B&C image (not recommended).

`Win10MasterDeployment.zip` - Single TS designed to deploy using a vanilla image.

`ModularOSD.zip` - Newer version of the master deployment, requires SCCM CB 1710+ with nested task sequences enabled.
  - Disable User Generated Feedback and Disable Typing Telemetry steps had there .reg moved to \depreciated, so thoses step should be removed or disabled by default
