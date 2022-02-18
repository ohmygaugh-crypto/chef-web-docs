+++
title = "PowershellInstallWindowsFeature"

+++

<!-- This content is automatically generated. See https://github.com/chef/chef-web-docs/blob/main/generated/README.md -->

The department is: `PowershellInstallWindowsFeature`

The full name of the cop is: `Chef/Modernize/PowershellInstallWindowsFeature`

| Enabled by default | Supports autocorrection | Target Chef Version |
| --- | --- | --- |
| Enabled | No | 14.0+ |

## Examples


#### incorrect

```ruby
powershell_script 'Install Feature' do
  code 'Install-WindowsFeature -Name "Net-framework-Core"'
end
```

## Configurable attributes

<table>
<tbody><tr>
<th>Name</th>
<th>Default value</th>
<th>Configurable values</th>
</tr>
<tr>
<td style="text-align:center">Version Added</td>
<td style="text-align:center">5.5.0</td>
<td style="text-align:center">String</td>
</tr>
<tr><td style="text-align:center">Include</td>
<td style="text-align:center"><ul>
</ul>
</td>
<td style="text-align:center">Array</td>
</tr></tbody></table>