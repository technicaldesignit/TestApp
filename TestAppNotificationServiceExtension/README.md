Add the next code to your app project:

```xml
<ItemGroup>
    <ProjectReference Include="..\TestAppNotificationServiceExtension\TestAppNotificationServiceExtension.csproj">
        <IsAppExtension>true</IsAppExtension>
        <IsWatchApp>false</IsWatchApp>
    </ProjectReference>
</ItemGroup>
```