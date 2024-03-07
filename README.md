# CyberChefDemo

https://gchq.github.io/CyberChef/

# Installation

## Manually

1. Go to https://gchq.github.io/CyberChef/
2. Click "Download CyberChef"
3. Click "Download Zip File"
4. Extract
5. Run `CyberChef_vX.Y.Z.html`

## Chocolatey

https://community.chocolatey.org/packages/cyberchef

1. Run `choco install cyberchef`
2. Installs a shortcut in `C:\Users\YourName\Desktop` (not your OneDrive desktop folder if you're using that)
3. You can still search for `CyberChef.lnk`, or open <file:///C:/ProgramData/chocolatey/lib/cyberchef/tools/CyberChef_vx.y.z.html> in your browser

# Demos

## Base 64 decode

* [Example](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=SUNBZ0lDQWdJQ0FnS0NBZ0lDQWdJQ0FnS1EwS0lDQWdJQ0FnSUNBZ1R5QWdJQ0FnSUNBZ1R3MEtJQ0FnSUNBZ0lDQWdLQ2tnSUNBZ0lDQW9LUTBLSUNBZ0lDQWdJQ0FnSUU5dkxtNXVMbTlQRFFvZ0lDQWdJQ0FnSUNBZ0lGOXRiVzF0WHcwS0lDQWdJQ0FnSUNBZ1hDOWZiVzF0YlY5Y0x3MEtJQ0FnSUNBZ0lDQWdYQzlmYlcxdGJWOWNMdzBLSUNBZ0lDQWdJQ0FnWEM5ZmJXMXRiVjljTHcwS0lDQWdJQ0FnSUNBZ1hDOGdiVzF0YlNCY0x3MEtJQ0FnSUNBZ0lDQWdJQ0FnSUc1dURRb2dJQ0FnSUNBZ0lDQWdJQ0FnS0NrTkNpQWdJQ0FnSUNBZ0lDQWdJQ0FvS1EwS0lDQWdJQ0FnSUNBZ0lDQWdJQ0FvS1NBZ0lDQXZEUW9nSUNBZ0lDQWdJQ0FnWVhCaklDQW9LVjlmS0NrTkNpQWdJQ0FnSUNBZ0lDQWdJQ0FnSUNBbkxTMG4)

## Frequency distribution

* [Example](https://gchq.github.io/CyberChef/#recipe=Frequency_distribution(false,true)&input=VGhlIHF1aWNrIGJyb3duIGZveCBqdW1wcyBvdmVyIHRoZSBsYXp5IGRvZw)

## CSV to JSON

* [Example](https://gchq.github.io/CyberChef/#recipe=CSV_to_JSON(',','%5C%5Cr%5C%5Cn','Array%20of%20dictionaries')&input=TXIsQXNobGV5LFNlYWdyYXZlLFNlYWdyYXZlIFRyYWluaW5nIEx0ZA0KTXMsTWVsaXNzYSxJbGxzbGV5LElsbHNsZXkgQWdlbmN5IEx0ZA0KTXIsTGFycnksS2luZ3N0b24sS2luZ3N0b24gR2FyZGVuaW5nIFNlcnZpY2VzIEx0ZA0KTWlzcyxVbmEsVmlyZ2lsLEpld2VsIFNob3dyb29tcyBMdGQNCk1yLFJvZ2VyLE1hY2F2b3ksTWFjYXZveSBCdWlsZGVycyBMdGQNCk1ycyxTdXNhbixUaWxseSxUaWxseSBXb3Jrc2hvcHMgTHRkDQpNcixNYXJjdXMsR29vZGFjcmUsR29vZGFjcmUgVHJhY3RvcnMgTHRkDQpNaXNzLEFuZ2VsYSxEZXdpdCxEZXdpdCBQaG90b2dyYXBoeSBMdGQNCk1yLEN1cnRpcyxQb29sZSxQb29sZSBUZWNobm9sb2dpZXMgTHRkDQpNcnMsUGF1bGEsS2luZ2Zpc2hlcixLaW5nZmlzaGVyIENvbXB1dGVycyBMdGQNCk1yLENlY2lsLEhhcnJhZGluZSxIYXJyYWRpbmUgUHVibGlzaGluZyBMdGQNCk1zLENoYXJsb3R0ZSxBZGtpbnNvbixBZGtpbnNvbiBPZmZpY2UgRnVybml0dXJlIEx0ZA0KTXIsRG91Z2xhcyxVbWJyaWRnZSxDb3VudHJ5d2lkZSBDb25zdHJ1Y3Rpb24gTHRkDQpNaXNzLFJ1YnksVGFsYm90LFRhbGJvdCBNYW51ZmFjdHVyaW5nIEx0ZA0KTXIsS2VubmV0aCxOaWdodGluZ2FsZSxOaWdodGluZ2FsZSBGaW5pc2hpbmcgTHRkDQpNcyxYYXJpYSxPc3dhbGQsT3N3YWxkIEJ1aWxkaW5nIE1hdGVyaWFscyBMdGQNCk1yLENocmlzdGlhbixQb3BwbGV3ZWxsLFN1cGVyIEhpcmUgQ2FycyBMdGQNCk1zLEFkZWxlLFZlbm4sVmVubiBIZWFsdGggUHJvZHVjdHMgTHRkDQpNcixKb2UsV2FsY290dCxXYWxjb3R0IEZydWl0IEltcG9ydGVycyBMdGQNCk1zLEhhbm5haCxUYXJidWNrLFRhcmJ1Y2sgTHV4dXJ5IENhcnMgTHRkDQpNcixaYW5lLEhhbmNvY2ssUHJlbWllciBUcmFjdG9ycyBMdGQNCk1zLExpbHksWWFyZGxleSxZYXJkbGV5IFByaW50aW5nIEx0ZA0KTXIsUmVnaW5hbGQsRml0emdlcmFsZCxGaXR6Z2VyYWxkIENhbXBpbmcgU3VwcGxpZXMgTHRkDQpNaXNzLERhbmllbGxlLFRlYmJpdCxFYXN0IFZpZXcgRGlzcG9zYWwgTHRkDQpNcixIYXJyeSxZYXJkbGV5LFlhcmRsZXkgQ2FyIFJlcGFpcnMgTHRkDQpNcyxDaGVsc2VhLFdpbG1vdHQsTm9ydGggU2lkZSBMaWdodGluZyBTZXJ2aWNlcyBMdGQNCk1yLERhdmlkLFBvcGUsUG9wZSBDYXRlcmVycyBMdGQNCk1zLFRhbW15LExlbm5vbixMZW5ub24gQ2FyZSBTZXJ2aWNlcyBMdGQNCk1yLEdvcmRvbixTZWFncmF2ZSxSaXZlcnNpZGUgVGlsZXMgTHRkDQpNaXNzLFplbGRhLENhcnRlcixDYXJ0ZXIgU2lnbnMgTHRkDQpNcixTdGV2ZW4sTmV3bWFuLEJldHRlciBFbmdpbmVlcmluZyBMdGQNCk1pc3MsU2FuZHJhLEluZ3JhbSxJbmdyYW0gQnVpbGRpbmcgTWF0ZXJpYWxzIEx0ZA0KTXIsTWFyY3VzLEhhbWlsdG9uLEhhbWlsdG9uIFNwb3J0aW5nIEdvb2RzIEx0ZA0KTWlzcyxTdXNhbixNb3JsZXksTW9ybGV5IERpc3Bvc2FsIEx0ZA0KTXIsSmFtaWUsQmFya2VyLEJhcmtlciBIZWFsdGggUHJvZHVjdHMgTHRkDQpNaXNzLEVtbWEsSGFsbHdvcnRoLEhhbGx3b3J0aCBDbGVhbmluZyBQcm9kdWN0cyBMdGQNCk1yLEphY2ssRmlzaGVyLEZpc2hlciBMb2dpc3RpY3MgTHRkDQpNaXNzLFJpdGEsQXRraW5zLEF0a2lucyBCYWtlcnkgTHRkDQpNcixSb25hbGQsRGl4b24sRGl4b24gTnVyc2luZyBTdXBwbGllcyBMdGQNCk1pc3MsTWFyaWx5bixXcmlnaHQsV3JpZ2h0IEFkdmVydGlzaW5nIEx0ZA0KTXIsUGF0cmljayxQcmVzdG9uLFByZXN0b24gRnVybmlzaGluZ3MgTHRkDQpNcyxOaW5hLEVsbGlzLEVsbGlzIENvbXB1dGluZyBMdGQNCk1yLE1hdHRoZXcsUm9kZ2VycyxSb2RnZXJzIFdhc3RlIERpc3Bvc2FsIEx0ZA0KTWlzcyxNYXJnYXJldCxXcmFwc29uLFdyYXBzb24gSG9tZSBTZXJ2aWNlcyBMdGQNCk1yLEFsYmVydCxCb3lsZSxCb3lsZSBDaGVtaWNhbHMgTHRkDQpNcnMsUml0YSxQYXhtYW4sUGF4bWFuIFNlY3VyaXR5IEx0ZA0KTXIsQXNobGV5LEVubmlzLEVubmlzIFdhdGNoZXMgTHRkDQpNaXNzLFN0YWN5LEZhaXJjaGlsZCxGYWlyY2hpbGQgQ2lyY3VpdHJ5IEx0ZA0KTXIsRG9uYWxkLENhcnR3cmlnaHQsQ2FydHdyaWdodCBPZmYgUm9hZCBWZWhpY2xlcyBMdGQNCk1ycyxIZWxlbixIYXJwZXIsSGFycGVyIEFwcGxpYW5jZXMgTHRk)

## Fuzzy Match

* [Example](https://gchq.github.io/CyberChef/#recipe=Fuzzy_Match('King',15,0,30,15,-5,-15,-1)&input=TXIsQXNobGV5LFNlYWdyYXZlLFNlYWdyYXZlIFRyYWluaW5nIEx0ZA0KTXMsTWVsaXNzYSxJbGxzbGV5LElsbHNsZXkgQWdlbmN5IEx0ZA0KTXIsTGFycnksS2luZ3N0b24sS2luZ3N0b24gR2FyZGVuaW5nIFNlcnZpY2VzIEx0ZA0KTWlzcyxVbmEsVmlyZ2lsLEpld2VsIFNob3dyb29tcyBMdGQNCk1yLFJvZ2VyLE1hY2F2b3ksTWFjYXZveSBCdWlsZGVycyBMdGQNCk1ycyxTdXNhbixUaWxseSxUaWxseSBXb3Jrc2hvcHMgTHRkDQpNcixNYXJjdXMsR29vZGFjcmUsR29vZGFjcmUgVHJhY3RvcnMgTHRkDQpNaXNzLEFuZ2VsYSxEZXdpdCxEZXdpdCBQaG90b2dyYXBoeSBMdGQNCk1yLEN1cnRpcyxQb29sZSxQb29sZSBUZWNobm9sb2dpZXMgTHRkDQpNcnMsUGF1bGEsS2luZ2Zpc2hlcixLaW5nZmlzaGVyIENvbXB1dGVycyBMdGQNCk1yLENlY2lsLEhhcnJhZGluZSxIYXJyYWRpbmUgUHVibGlzaGluZyBMdGQNCk1zLENoYXJsb3R0ZSxBZGtpbnNvbixBZGtpbnNvbiBPZmZpY2UgRnVybml0dXJlIEx0ZA0KTXIsRG91Z2xhcyxVbWJyaWRnZSxDb3VudHJ5d2lkZSBDb25zdHJ1Y3Rpb24gTHRkDQpNaXNzLFJ1YnksVGFsYm90LFRhbGJvdCBNYW51ZmFjdHVyaW5nIEx0ZA0KTXIsS2VubmV0aCxOaWdodGluZ2FsZSxOaWdodGluZ2FsZSBGaW5pc2hpbmcgTHRkDQpNcyxYYXJpYSxPc3dhbGQsT3N3YWxkIEJ1aWxkaW5nIE1hdGVyaWFscyBMdGQNCk1yLENocmlzdGlhbixQb3BwbGV3ZWxsLFN1cGVyIEhpcmUgQ2FycyBMdGQNCk1zLEFkZWxlLFZlbm4sVmVubiBIZWFsdGggUHJvZHVjdHMgTHRkDQpNcixKb2UsV2FsY290dCxXYWxjb3R0IEZydWl0IEltcG9ydGVycyBMdGQNCk1zLEhhbm5haCxUYXJidWNrLFRhcmJ1Y2sgTHV4dXJ5IENhcnMgTHRkDQpNcixaYW5lLEhhbmNvY2ssUHJlbWllciBUcmFjdG9ycyBMdGQNCk1zLExpbHksWWFyZGxleSxZYXJkbGV5IFByaW50aW5nIEx0ZA0KTXIsUmVnaW5hbGQsRml0emdlcmFsZCxGaXR6Z2VyYWxkIENhbXBpbmcgU3VwcGxpZXMgTHRkDQpNaXNzLERhbmllbGxlLFRlYmJpdCxFYXN0IFZpZXcgRGlzcG9zYWwgTHRkDQpNcixIYXJyeSxZYXJkbGV5LFlhcmRsZXkgQ2FyIFJlcGFpcnMgTHRkDQpNcyxDaGVsc2VhLFdpbG1vdHQsTm9ydGggU2lkZSBMaWdodGluZyBTZXJ2aWNlcyBMdGQNCk1yLERhdmlkLFBvcGUsUG9wZSBDYXRlcmVycyBMdGQNCk1zLFRhbW15LExlbm5vbixMZW5ub24gQ2FyZSBTZXJ2aWNlcyBMdGQNCk1yLEdvcmRvbixTZWFncmF2ZSxSaXZlcnNpZGUgVGlsZXMgTHRkDQpNaXNzLFplbGRhLENhcnRlcixDYXJ0ZXIgU2lnbnMgTHRkDQpNcixTdGV2ZW4sTmV3bWFuLEJldHRlciBFbmdpbmVlcmluZyBMdGQNCk1pc3MsU2FuZHJhLEluZ3JhbSxJbmdyYW0gQnVpbGRpbmcgTWF0ZXJpYWxzIEx0ZA0KTXIsTWFyY3VzLEhhbWlsdG9uLEhhbWlsdG9uIFNwb3J0aW5nIEdvb2RzIEx0ZA0KTWlzcyxTdXNhbixNb3JsZXksTW9ybGV5IERpc3Bvc2FsIEx0ZA0KTXIsSmFtaWUsQmFya2VyLEJhcmtlciBIZWFsdGggUHJvZHVjdHMgTHRkDQpNaXNzLEVtbWEsSGFsbHdvcnRoLEhhbGx3b3J0aCBDbGVhbmluZyBQcm9kdWN0cyBMdGQNCk1yLEphY2ssRmlzaGVyLEZpc2hlciBMb2dpc3RpY3MgTHRkDQpNaXNzLFJpdGEsQXRraW5zLEF0a2lucyBCYWtlcnkgTHRkDQpNcixSb25hbGQsRGl4b24sRGl4b24gTnVyc2luZyBTdXBwbGllcyBMdGQNCk1pc3MsTWFyaWx5bixXcmlnaHQsV3JpZ2h0IEFkdmVydGlzaW5nIEx0ZA0KTXIsUGF0cmljayxQcmVzdG9uLFByZXN0b24gRnVybmlzaGluZ3MgTHRkDQpNcyxOaW5hLEVsbGlzLEVsbGlzIENvbXB1dGluZyBMdGQNCk1yLE1hdHRoZXcsUm9kZ2VycyxSb2RnZXJzIFdhc3RlIERpc3Bvc2FsIEx0ZA0KTWlzcyxNYXJnYXJldCxXcmFwc29uLFdyYXBzb24gSG9tZSBTZXJ2aWNlcyBMdGQNCk1yLEFsYmVydCxCb3lsZSxCb3lsZSBDaGVtaWNhbHMgTHRkDQpNcnMsUml0YSxQYXhtYW4sUGF4bWFuIFNlY3VyaXR5IEx0ZA0KTXIsQXNobGV5LEVubmlzLEVubmlzIFdhdGNoZXMgTHRkDQpNaXNzLFN0YWN5LEZhaXJjaGlsZCxGYWlyY2hpbGQgQ2lyY3VpdHJ5IEx0ZA0KTXIsRG9uYWxkLENhcnR3cmlnaHQsQ2FydHdyaWdodCBPZmYgUm9hZCBWZWhpY2xlcyBMdGQNCk1ycyxIZWxlbixIYXJwZXIsSGFycGVyIEFwcGxpYW5jZXMgTHRk)

## Magic

* [Example](https://gchq.github.io/CyberChef/#recipe=Magic(3,false,false,'')&input=V1VhZ3dzaWFlNm1QOGdOdENDTFVGcENwQ0IyNlJtQkRvREQ4UGFjZEFtekF6QlZqa0syUXN0RlhhS2hwQzZpVVM3UkhxWHJKdEZpc29SU2dvSjR3aGptMWFybTg2NHFhTnE0UmNmVW1MSHJjc0FhWmM1VFhDWWlmTmRnUzgzZ0RlZWpHWDQ2Z2FpTXl1QlY2RXNrSHQxc2NnSjg4eDJ0TlNvdFFEd2JHWTFtbUNvYjJBUkdGdkNLWU5xaU45aXBNcTFaVTFtZ2tkYk51R2NiNzZhUnRZV2hDR1VjOGc5M1VKdWRoYjhodHNoZVpud1RwZ3FoeDgzU1ZKU1pYTVhVakpUMnptcEM3dVhXdHVtcW9rYmRTaTg4WXRrV0RBYzFUb291aDJvSDRENGRkbU5LSldVRHBNd21uZ1VtSzE0eHdtb21jY1BRRTloTTE3MkFQblNxd3hkS1ExNzJSa2NBc3lzbm1qNWdHdFJtVk5OaDJzMzU5d3I2bVMyUVJQ)

## Calling HTTP APIs 

* [Example](https://gchq.github.io/CyberChef/#recipe=HTTP_request('GET','https://pokeapi.co/api/v2/pokemon/ditto','','Cross-Origin%20Resource%20Sharing',false)Syntax_highlighter('json'/disabled)JSON_Beautify('%20%20%20%20',false,true/disabled)Add_line_numbers(/disabled))

## EXIF data

* [Example](https://gchq.github.io/CyberChef/#recipe=Extract_EXIF()&input=/9j/4AAQSkZJRgABAQEA8ADwAAD/4QjiRXhpZgAASUkqAAgAAAAJAA8BAgASAAAAegAAABABAgAKAAAAjAAAABIBAwABAAAAAQAAABoBBQABAAAAlgAAABsBBQABAAAAngAAACgBAwABAAAAAgAAADEBAgALAAAApgAAADIBAgAUAAAAsgAAAGmHBAABAAAAxgAAANgBAABOSUtPTiBDT1JQT1JBVElPTgBOSUtPTiBENzAA8AAAAAEAAADwAAAAAQAAAEdJTVAgMi40LjUAADIwMDg6MDc6MzEgMTA6MDM6NDQAEACaggUAAQAAAIwBAACdggUAAQAAAJQBAAAiiAMAAQAAAAEAAAAniAMAAQAAAMgAAAADkAIAFAAAAJwBAAABkgoAAQAAALABAAACkgUAAQAAALgBAAAEkgoAAQAAAMABAAAFkgUAAQAAAMgBAAAHkgMAAQAAAAIAAAAJkgMAAQAAAAAAAAAKkgUAAQAAANABAAABoAMAAQAAAAEAAAACoAQAAQAAAGQAAAADoAQAAQAAAEIAAAAFpAMAAQAAAJYAAAAAAAAAAQAAAMgAAAAJAAAAAQAAADIwMDg6MDM6MTUgMDk6NTI6MDEA0KJ0AEBCDwCBrAkAoIYBAP////8BAAAAIQAAAAoAAABkAAAAAQAAAAYAAwEDAAEAAAAGAAAAGgEFAAEAAAAmAgAAGwEFAAEAAAAuAgAAKAEDAAEAAAACAAAAAQIEAAEAAAA2AgAAAgIEAAEAAACkBgAAAAAAAEgAAAABAAAASAAAAAEAAAD/2P/gABBKRklGAAEBAAABAAEAAP/bAEMACAYGBwYFCAcHBwkJCAoMFA0MCwsMGRITDxQdGh8eHRocHCAkLicgIiwjHBwoNyksMDE0NDQfJzk9ODI8LjM0Mv/bAEMBCQkJDAsMGA0NGDIhHCEyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMv/AABEIACsAQgMBIgACEQEDEQH/xAAfAAABBQEBAQEBAQAAAAAAAAAAAQIDBAUGBwgJCgv/xAC1EAACAQMDAgQDBQUEBAAAAX0BAgMABBEFEiExQQYTUWEHInEUMoGRoQgjQrHBFVLR8CQzYnKCCQoWFxgZGiUmJygpKjQ1Njc4OTpDREVGR0hJSlNUVVZXWFlaY2RlZmdoaWpzdHV2d3h5eoOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4eLj5OXm5%2Bjp6vHy8/T19vf4%2Bfr/xAAfAQADAQEBAQEBAQEBAAAAAAAAAQIDBAUGBwgJCgv/xAC1EQACAQIEBAMEBwUEBAABAncAAQIDEQQFITEGEkFRB2FxEyIygQgUQpGhscEJIzNS8BVictEKFiQ04SXxFxgZGiYnKCkqNTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqCg4SFhoeIiYqSk5SVlpeYmZqio6Slpqeoqaqys7S1tre4ubrCw8TFxsfIycrS09TV1tfY2dri4%2BTl5ufo6ery8/T19vf4%2Bfr/2gAMAwEAAhEDEQA/AO5stJW0sIbSB0ihhG6R1Pyr6kt/Ef0rjvF%2ButKFt7RGkgh/1MIbk/7Z%2BvNa/jTxXFAi6fYI8yE5Ecf3pfVj6KK8c8T3Md3qRct%2B8U7cZ6j39K8KFL2rt9n8/L0KULq/Q3m1XUp3jsJrrybYKWUyvsVW9MBevvUY1/VNMl%2BzWllaXR25MkUplBB/KudsLp5UNsJ0i2ozx%2BbyrsOdpz0zVIRarcs04t2Gct8qBePYV3KCSs9i%2Ba2zJdVvJLi%2BeSaIRS5%2BZQeBUdld3pE9rZxgiQDc2On40WcN1qVz5K25mP8AEQOVHrmrgiuNDkkjVTvkG4xlhnHbiqlotETJ3Ra0bUNQaxvraMosDqPNSTGH/A96szTW1zZFEjFvOoUHYvoc5HoelZVzqEGoxqjWkxlwA5TuR3/KrtvJBeSra2cLgQr/AK9j91cfxVEotamaV3Y0BrcijAeAgcAsOT9feiry6JCVBMMjEjrkDP4UVlzrub%2BwqHKR3fiW1vrnU7q3nV7iEjz5IyVUdRjtWZc%2BILu4iAnSCTIKljGM898%2BtfQniq%2B8PaPppWOwh%2B3v/q408xdv%2B0RgV4Xrmni5Z7gyhJGbcc8lq2o102k0reRnzO1iMWMY0X7elyu9GAMZznJ6Y96uWF5favq8M8krxGGLDMBwQOmfrUOnafPdbYIEaQuw7dW7YHrzW%2BbH%2BymNnLcLEyTbbliuSrY6Y9v503JaihZ7ktvNem5mstAtt9xcOfMkVM7Sepz0HtWxB8KpjILnV9R2u/zMRyxP1PX8qy08ZWXh68lfSYpJN6gB7h8ZYfxFR3rD1XxtrGsTEXN7MI27RfIv6cn8a55KrLSGiKk7vQ9Kt9P8N%2BG4m8qZ3mIwS8vX%2Bn6CsxYrXWLtjaW8QiDDzJEGAxByBnvXKaTaW2qq0YnWK2hAa5uZTh3J7DPQV1p8Xado2k%2BVptm88cIAMhXbGvPcmudUZRle92bU6cYvmmzolsQFA8sdPSiuKHxB1VwGS2s9p5HXp%2BdFaexmdX1in5/cclcDU0naS7s5xIT9%2BXLEmr1j4c1PUmWYW0lw46RqpwPxr3fxFpdjskP2aPPripvh7dzzG4tZHDQRD5EKjitKNS9T2bVmeU97HmWmeEfGMYb%2BzrNbF2XHnSEb1HouAcfhVKT4dapvZbrUdjEkvshLMxPUkk9a%2BkjGiuSFwfasDUriSKb92QpJ5IUVpiIOmrqX4FWdjw5fhiVOWur2UEYP7gH/ABpbj4XXMoAia6aMchXiwP6V7Lcs7Qhi7k/7xrKlnkDY3muN1asX8QnfueLXHhm%2B0p2ECwyyQnd5RjOG9jzWJ4k1rV9WEdrcpHbpEMNDESqsc9SM16hK7nXbjLMcNxuOa848YSsNYZsJkj%2B4P8K7KLcpa7jU5Wsc4r3iqFErgAYAElFRm7mz1X/vgf4UV1WY7s//2f/%2BABdjb21tZW50IGluIEdJTVAgMi40LjX/4RR3aHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wLwA8P3hwYWNrZXQgYmVnaW49J%2B%2B7vycgaWQ9J1c1TTBNcENlaGlIenJlU3pOVGN6a2M5ZCc/Pgo8eDp4bXBtZXRhIHhtbG5zOng9J2Fkb2JlOm5zOm1ldGEvJz4KPHJkZjpSREYgeG1sbnM6cmRmPSdodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjJz4KCiA8cmRmOkRlc2NyaXB0aW9uIHhtbG5zOmNycz0naHR0cDovL25zLmFkb2JlLmNvbS9jYW1lcmEtcmF3LXNldHRpbmdzLzEuMC8nPgogIDxjcnM6VmVyc2lvbj4zLjA8L2NyczpWZXJzaW9uPgogIDxjcnM6UmF3RmlsZU5hbWU%2BRFNDXzE4MDEuTkVGPC9jcnM6UmF3RmlsZU5hbWU%2BCiAgPGNyczpXaGl0ZUJhbGFuY2U%2BQXMgU2hvdDwvY3JzOldoaXRlQmFsYW5jZT4KICA8Y3JzOlRlbXBlcmF0dXJlPjQyNTA8L2NyczpUZW1wZXJhdHVyZT4KICA8Y3JzOlRpbnQ%2BLTM8L2NyczpUaW50PgogIDxjcnM6RXhwb3N1cmU%2BLTAuNTA8L2NyczpFeHBvc3VyZT4KICA8Y3JzOkF1dG9TaGFkb3dzPlRydWU8L2NyczpBdXRvU2hhZG93cz4KICA8Y3JzOlNoYWRvd3M%2BMjwvY3JzOlNoYWRvd3M%2BCiAgPGNyczpCcmlnaHRuZXNzPjUwPC9jcnM6QnJpZ2h0bmVzcz4KICA8Y3JzOkNvbnRyYXN0PjA8L2NyczpDb250cmFzdD4KICA8Y3JzOlNhdHVyYXRpb24%2BMDwvY3JzOlNhdHVyYXRpb24%2BCiAgPGNyczpTaGFycG5lc3M%2BODU8L2NyczpTaGFycG5lc3M%2BCiAgPGNyczpMdW1pbmFuY2VTbW9vdGhpbmc%2BMDwvY3JzOkx1bWluYW5jZVNtb290aGluZz4KICA8Y3JzOkNvbG9yTm9pc2VSZWR1Y3Rpb24%2BMjU8L2NyczpDb2xvck5vaXNlUmVkdWN0aW9uPgogIDxjcnM6Q2hyb21hdGljQWJlcnJhdGlvblI%2BMDwvY3JzOkNocm9tYXRpY0FiZXJyYXRpb25SPgogIDxjcnM6Q2hyb21hdGljQWJlcnJhdGlvbkI%2BMDwvY3JzOkNocm9tYXRpY0FiZXJyYXRpb25CPgogIDxjcnM6VmlnbmV0dGVBbW91bnQ%2BMDwvY3JzOlZpZ25ldHRlQW1vdW50PgogIDxjcnM6U2hhZG93VGludD4wPC9jcnM6U2hhZG93VGludD4KICA8Y3JzOlJlZEh1ZT4wPC9jcnM6UmVkSHVlPgogIDxjcnM6UmVkU2F0dXJhdGlvbj4wPC9jcnM6UmVkU2F0dXJhdGlvbj4KICA8Y3JzOkdyZWVuSHVlPjA8L2NyczpHcmVlbkh1ZT4KICA8Y3JzOkdyZWVuU2F0dXJhdGlvbj4wPC9jcnM6R3JlZW5TYXR1cmF0aW9uPgogIDxjcnM6Qmx1ZUh1ZT4wPC9jcnM6Qmx1ZUh1ZT4KICA8Y3JzOkJsdWVTYXR1cmF0aW9uPjA8L2NyczpCbHVlU2F0dXJhdGlvbj4KICA8Y3JzOlRvbmVDdXJ2ZU5hbWU%2BTWVkaXVtIENvbnRyYXN0PC9jcnM6VG9uZUN1cnZlTmFtZT4KICA8Y3JzOlRvbmVDdXJ2ZT4KICAgPHJkZjpCYWc%2BCiAgICA8cmRmOmxpPjAsIDA8L3JkZjpsaT4KICAgIDxyZGY6bGk%2BMzIsIDIyPC9yZGY6bGk%2BCiAgICA8cmRmOmxpPjY0LCA1NjwvcmRmOmxpPgogICAgPHJkZjpsaT4xMjgsIDEyODwvcmRmOmxpPgogICAgPHJkZjpsaT4xOTIsIDE5NjwvcmRmOmxpPgogICAgPHJkZjpsaT4yNTUsIDI1NTwvcmRmOmxpPgogICA8L3JkZjpCYWc%2BCiAgPC9jcnM6VG9uZUN1cnZlPgogIDxjcnM6Q2FtZXJhUHJvZmlsZT5BQ1IgMi40PC9jcnM6Q2FtZXJhUHJvZmlsZT4KICA8Y3JzOkhhc1NldHRpbmdzPlRydWU8L2NyczpIYXNTZXR0aW5ncz4KICA8Y3JzOkhhc0Nyb3A%2BRmFsc2U8L2NyczpIYXNDcm9wPgogPC9yZGY6RGVzY3JpcHRpb24%2BCgogPHJkZjpEZXNjcmlwdGlvbiB4bWxuczpleGlmPSdodHRwOi8vbnMuYWRvYmUuY29tL2V4aWYvMS4wLyc%2BCiAgPGV4aWY6RXhwb3N1cmVUaW1lPjEvMjAwPC9leGlmOkV4cG9zdXJlVGltZT4KICA8ZXhpZjpTaHV0dGVyU3BlZWRWYWx1ZT43NjQzODU2LzEwMDAwMDA8L2V4aWY6U2h1dHRlclNwZWVkVmFsdWU%2BCiAgPGV4aWY6Rk51bWJlcj45LzE8L2V4aWY6Rk51bWJlcj4KICA8ZXhpZjpBcGVydHVyZVZhbHVlPjYzMzk4NS8xMDAwMDA8L2V4aWY6QXBlcnR1cmVWYWx1ZT4KICA8ZXhpZjpFeHBvc3VyZVByb2dyYW0%2BMTwvZXhpZjpFeHBvc3VyZVByb2dyYW0%2BCiAgPGV4aWY6SVNPU3BlZWRSYXRpbmdzPgogICA8cmRmOlNlcT4KICAgIDxyZGY6bGk%2BMjAwPC9yZGY6bGk%2BCiAgIDwvcmRmOlNlcT4KICA8L2V4aWY6SVNPU3BlZWRSYXRpbmdzPgogIDxleGlmOkRhdGVUaW1lT3JpZ2luYWw%2BMjAwOC0wMy0xNVQwOTo1MjowMS0wNDowMDwvZXhpZjpEYXRlVGltZU9yaWdpbmFsPgogIDxleGlmOkV4cG9zdXJlQmlhc1ZhbHVlPi0xLzE8L2V4aWY6RXhwb3N1cmVCaWFzVmFsdWU%2BCiAgPGV4aWY6TWF4QXBlcnR1cmVWYWx1ZT4zMy8xMDwvZXhpZjpNYXhBcGVydHVyZVZhbHVlPgogIDxleGlmOk1ldGVyaW5nTW9kZT4yPC9leGlmOk1ldGVyaW5nTW9kZT4KICA8ZXhpZjpGbGFzaCByZGY6cGFyc2VUeXBlPSdSZXNvdXJjZSc%2BCiAgIDxleGlmOkZpcmVkPkZhbHNlPC9leGlmOkZpcmVkPgogICA8ZXhpZjpSZXR1cm4%2BMDwvZXhpZjpSZXR1cm4%2BCiAgIDxleGlmOk1vZGU%2BMDwvZXhpZjpNb2RlPgogICA8ZXhpZjpGdW5jdGlvbj5GYWxzZTwvZXhpZjpGdW5jdGlvbj4KICAgPGV4aWY6UmVkRXllTW9kZT5GYWxzZTwvZXhpZjpSZWRFeWVNb2RlPgogIDwvZXhpZjpGbGFzaD4KICA8ZXhpZjpGb2NhbExlbmd0aD4xMDAvMTwvZXhpZjpGb2NhbExlbmd0aD4KICA8ZXhpZjpGb2NhbExlbmd0aEluMzVtbUZpbG0%2BMTUwPC9leGlmOkZvY2FsTGVuZ3RoSW4zNW1tRmlsbT4KICA8ZXhpZjpQaXhlbFhEaW1lbnNpb24%2BMjczMDwvZXhpZjpQaXhlbFhEaW1lbnNpb24%2BCiAgPGV4aWY6UGl4ZWxZRGltZW5zaW9uPjE3OTA8L2V4aWY6UGl4ZWxZRGltZW5zaW9uPgogIDxleGlmOkNvbG9yU3BhY2U%2BMTwvZXhpZjpDb2xvclNwYWNlPgogIDxleGlmOk5hdGl2ZURpZ2VzdD4zNjg2NCw0MDk2MCw0MDk2MSwzNzEyMSwzNzEyMiw0MDk2Miw0MDk2MywzNzUxMCw0MDk2NCwzNjg2NywzNjg2OCwzMzQzNCwzMzQzNywzNDg1MCwzNDg1MiwzNDg1NSwzNDg1NiwzNzM3NywzNzM3OCwzNzM3OSwzNzM4MCwzNzM4MSwzNzM4MiwzNzM4MywzNzM4NCwzNzM4NSwzNzM4NiwzNzM5Niw0MTQ4Myw0MTQ4NCw0MTQ4Niw0MTQ4Nyw0MTQ4OCw0MTQ5Miw0MTQ5Myw0MTQ5NSw0MTcyOCw0MTcyOSw0MTczMCw0MTk4NSw0MTk4Niw0MTk4Nyw0MTk4OCw0MTk4OSw0MTk5MCw0MTk5MSw0MTk5Miw0MTk5Myw0MTk5NCw0MTk5NSw0MTk5Niw0MjAxNiwwLDIsNCw1LDYsNyw4LDksMTAsMTEsMTIsMTMsMTQsMTUsMTYsMTcsMTgsMjAsMjIsMjMsMjQsMjUsMjYsMjcsMjgsMzA7OUZGMzgxRENBNjZDQ0ZBOTMzOUYyMUVBQzA0OTM4ODM8L2V4aWY6TmF0aXZlRGlnZXN0PgogPC9yZGY6RGVzY3JpcHRpb24%2BCgogPHJkZjpEZXNjcmlwdGlvbiB4bWxuczphdXg9J2h0dHA6Ly9ucy5hZG9iZS5jb20vZXhpZi8xLjAvYXV4Lyc%2BCiAgPGF1eDpMZW5zPjEwMC4wIG1tIGYvMi44PC9hdXg6TGVucz4KIDwvcmRmOkRlc2NyaXB0aW9uPgoKIDxyZGY6RGVzY3JpcHRpb24geG1sbnM6dGlmZj0naHR0cDovL25zLmFkb2JlLmNvbS90aWZmLzEuMC8nPgogIDx0aWZmOk1ha2U%2BTklLT04gQ09SUE9SQVRJT048L3RpZmY6TWFrZT4KICA8dGlmZjpNb2RlbD5OSUtPTiBENzA8L3RpZmY6TW9kZWw%2BCiAgPHRpZmY6SW1hZ2VXaWR0aD4zMDA4PC90aWZmOkltYWdlV2lkdGg%2BCiAgPHRpZmY6SW1hZ2VMZW5ndGg%2BMjAwMDwvdGlmZjpJbWFnZUxlbmd0aD4KICA8dGlmZjpCaXRzUGVyU2FtcGxlPgogICA8cmRmOlNlcT4KICAgIDxyZGY6bGk%2BODwvcmRmOmxpPgogICAgPHJkZjpsaT44PC9yZGY6bGk%2BCiAgICA8cmRmOmxpPjg8L3JkZjpsaT4KICAgPC9yZGY6U2VxPgogIDwvdGlmZjpCaXRzUGVyU2FtcGxlPgogIDx0aWZmOlBob3RvbWV0cmljSW50ZXJwcmV0YXRpb24%2BMjwvdGlmZjpQaG90b21ldHJpY0ludGVycHJldGF0aW9uPgogIDx0aWZmOlhSZXNvbHV0aW9uPjI0MDAwMDAvMTAwMDA8L3RpZmY6WFJlc29sdXRpb24%2BCiAgPHRpZmY6WVJlc29sdXRpb24%2BMjQwMDAwMC8xMDAwMDwvdGlmZjpZUmVzb2x1dGlvbj4KICA8dGlmZjpSZXNvbHV0aW9uVW5pdD4yPC90aWZmOlJlc29sdXRpb25Vbml0PgogIDx0aWZmOk9yaWVudGF0aW9uPjE8L3RpZmY6T3JpZW50YXRpb24%2BCiAgPHRpZmY6TmF0aXZlRGlnZXN0PjI1NiwyNTcsMjU4LDI1OSwyNjIsMjc0LDI3NywyODQsNTMwLDUzMSwyODIsMjgzLDI5NiwzMDEsMzE4LDMxOSw1MjksNTMyLDMwNiwyNzAsMjcxLDI3MiwzMDUsMzE1LDMzNDMyOzhGMTA1MkQzQjc5MzBGMzM2MUNFQTc0NzREOTcyOTE4PC90aWZmOk5hdGl2ZURpZ2VzdD4KIDwvcmRmOkRlc2NyaXB0aW9uPgoKIDxyZGY6RGVzY3JpcHRpb24geG1sbnM6eG1wPSdodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvJz4KICA8eG1wOkNyZWF0b3JUb29sPkFkb2JlIFBob3Rvc2hvcCBDUzIgV2luZG93czwveG1wOkNyZWF0b3JUb29sPgogIDx4bXA6TW9kaWZ5RGF0ZT4yMDA4LTAzLTE1VDE1OjE4OjMzLTA0OjAwPC94bXA6TW9kaWZ5RGF0ZT4KICA8eG1wOkNyZWF0ZURhdGU%2BMjAwOC0wMy0xNVQwOTo1MjowMS0wNDowMDwveG1wOkNyZWF0ZURhdGU%2BCiAgPHhtcDpNZXRhZGF0YURhdGU%2BMjAwOC0wMy0xNVQxNToxODozMy0wNDowMDwveG1wOk1ldGFkYXRhRGF0ZT4KIDwvcmRmOkRlc2NyaXB0aW9uPgoKIDxyZGY6RGVzY3JpcHRpb24geG1sbnM6eG1wTU09J2h0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8nPgogIDx4bXBNTTpEb2N1bWVudElEIHJkZjpyZXNvdXJjZT0ndXVpZDo3Mzc4QzJGMUMwRjJEQzExOTZDODlEMTAzOTg4QTAzRScgLz4KICA8eG1wTU06SW5zdGFuY2VJRD51dWlkOjc0NzhDMkYxQzBGMkRDMTE5NkM4OUQxMDM5ODhBMDNFPC94bXBNTTpJbnN0YW5jZUlEPgogPC9yZGY6RGVzY3JpcHRpb24%2BCgogPHJkZjpEZXNjcmlwdGlvbiB4bWxuczpkYz0naHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8nPgogIDxkYzpmb3JtYXQ%2BaW1hZ2UvanBlZzwvZGM6Zm9ybWF0PgogPC9yZGY6RGVzY3JpcHRpb24%2BCgogPHJkZjpEZXNjcmlwdGlvbiB4bWxuczpwaG90b3Nob3A9J2h0dHA6Ly9ucy5hZG9iZS5jb20vcGhvdG9zaG9wLzEuMC8nPgogIDxwaG90b3Nob3A6Q29sb3JNb2RlPjM8L3Bob3Rvc2hvcDpDb2xvck1vZGU%2BCiAgPHBob3Rvc2hvcDpJQ0NQcm9maWxlPnNSR0IgSUVDNjE5NjYtMi4xPC9waG90b3Nob3A6SUNDUHJvZmlsZT4KICA8cGhvdG9zaG9wOkhpc3Rvcnk%2BPC9waG90b3Nob3A6SGlzdG9yeT4KIDwvcmRmOkRlc2NyaXB0aW9uPgoKPC9yZGY6UkRGPgo8L3g6eG1wbWV0YT4KPD94cGFja2V0IGVuZD0ncic/Pgr/4gxYSUNDX1BST0ZJTEUAAQEAAAxITGlubwIQAABtbnRyUkdCIFhZWiAHzgACAAkABgAxAABhY3NwTVNGVAAAAABJRUMgc1JHQgAAAAAAAAAAAAAAAAAA9tYAAQAAAADTLUhQICAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABFjcHJ0AAABUAAAADNkZXNjAAABhAAAAGx3dHB0AAAB8AAAABRia3B0AAACBAAAABRyWFlaAAACGAAAABRnWFlaAAACLAAAABRiWFlaAAACQAAAABRkbW5kAAACVAAAAHBkbWRkAAACxAAAAIh2dWVkAAADTAAAAIZ2aWV3AAAD1AAAACRsdW1pAAAD%2BAAAABRtZWFzAAAEDAAAACR0ZWNoAAAEMAAAAAxyVFJDAAAEPAAACAxnVFJDAAAEPAAACAxiVFJDAAAEPAAACAx0ZXh0AAAAAENvcHlyaWdodCAoYykgMTk5OCBIZXdsZXR0LVBhY2thcmQgQ29tcGFueQAAZGVzYwAAAAAAAAASc1JHQiBJRUM2MTk2Ni0yLjEAAAAAAAAAAAAAABJzUkdCIElFQzYxOTY2LTIuMQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAWFlaIAAAAAAAAPNRAAEAAAABFsxYWVogAAAAAAAAAAAAAAAAAAAAAFhZWiAAAAAAAABvogAAOPUAAAOQWFlaIAAAAAAAAGKZAAC3hQAAGNpYWVogAAAAAAAAJKAAAA%2BEAAC2z2Rlc2MAAAAAAAAAFklFQyBodHRwOi8vd3d3LmllYy5jaAAAAAAAAAAAAAAAFklFQyBodHRwOi8vd3d3LmllYy5jaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABkZXNjAAAAAAAAAC5JRUMgNjE5NjYtMi4xIERlZmF1bHQgUkdCIGNvbG91ciBzcGFjZSAtIHNSR0IAAAAAAAAAAAAAAC5JRUMgNjE5NjYtMi4xIERlZmF1bHQgUkdCIGNvbG91ciBzcGFjZSAtIHNSR0IAAAAAAAAAAAAAAAAAAAAAAAAAAAAAZGVzYwAAAAAAAAAsUmVmZXJlbmNlIFZpZXdpbmcgQ29uZGl0aW9uIGluIElFQzYxOTY2LTIuMQAAAAAAAAAAAAAALFJlZmVyZW5jZSBWaWV3aW5nIENvbmRpdGlvbiBpbiBJRUM2MTk2Ni0yLjEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHZpZXcAAAAAABOk/gAUXy4AEM8UAAPtzAAEEwsAA1yeAAAAAVhZWiAAAAAAAEwJVgBQAAAAVx/nbWVhcwAAAAAAAAABAAAAAAAAAAAAAAAAAAAAAAAAAo8AAAACc2lnIAAAAABDUlQgY3VydgAAAAAAAAQAAAAABQAKAA8AFAAZAB4AIwAoAC0AMgA3ADsAQABFAEoATwBUAFkAXgBjAGgAbQByAHcAfACBAIYAiwCQAJUAmgCfAKQAqQCuALIAtwC8AMEAxgDLANAA1QDbAOAA5QDrAPAA9gD7AQEBBwENARMBGQEfASUBKwEyATgBPgFFAUwBUgFZAWABZwFuAXUBfAGDAYsBkgGaAaEBqQGxAbkBwQHJAdEB2QHhAekB8gH6AgMCDAIUAh0CJgIvAjgCQQJLAlQCXQJnAnECegKEAo4CmAKiAqwCtgLBAssC1QLgAusC9QMAAwsDFgMhAy0DOANDA08DWgNmA3IDfgOKA5YDogOuA7oDxwPTA%2BAD7AP5BAYEEwQgBC0EOwRIBFUEYwRxBH4EjASaBKgEtgTEBNME4QTwBP4FDQUcBSsFOgVJBVgFZwV3BYYFlgWmBbUFxQXVBeUF9gYGBhYGJwY3BkgGWQZqBnsGjAadBq8GwAbRBuMG9QcHBxkHKwc9B08HYQd0B4YHmQesB78H0gflB/gICwgfCDIIRghaCG4IggiWCKoIvgjSCOcI%2BwkQCSUJOglPCWQJeQmPCaQJugnPCeUJ%2BwoRCicKPQpUCmoKgQqYCq4KxQrcCvMLCwsiCzkLUQtpC4ALmAuwC8gL4Qv5DBIMKgxDDFwMdQyODKcMwAzZDPMNDQ0mDUANWg10DY4NqQ3DDd4N%2BA4TDi4OSQ5kDn8Omw62DtIO7g8JDyUPQQ9eD3oPlg%2BzD88P7BAJECYQQxBhEH4QmxC5ENcQ9RETETERTxFtEYwRqhHJEegSBxImEkUSZBKEEqMSwxLjEwMTIxNDE2MTgxOkE8UT5RQGFCcUSRRqFIsUrRTOFPAVEhU0FVYVeBWbFb0V4BYDFiYWSRZsFo8WshbWFvoXHRdBF2UXiReuF9IX9xgbGEAYZRiKGK8Y1Rj6GSAZRRlrGZEZtxndGgQaKhpRGncanhrFGuwbFBs7G2MbihuyG9ocAhwqHFIcexyjHMwc9R0eHUcdcB2ZHcMd7B4WHkAeah6UHr4e6R8THz4faR%2BUH78f6iAVIEEgbCCYIMQg8CEcIUghdSGhIc4h%2ByInIlUigiKvIt0jCiM4I2YjlCPCI/AkHyRNJHwkqyTaJQklOCVoJZclxyX3JicmVyaHJrcm6CcYJ0kneierJ9woDSg/KHEooijUKQYpOClrKZ0p0CoCKjUqaCqbKs8rAis2K2krnSvRLAUsOSxuLKIs1y0MLUEtdi2rLeEuFi5MLoIuty7uLyQvWi%2BRL8cv/jA1MGwwpDDbMRIxSjGCMbox8jIqMmMymzLUMw0zRjN/M7gz8TQrNGU0njTYNRM1TTWHNcI1/TY3NnI2rjbpNyQ3YDecN9c4FDhQOIw4yDkFOUI5fzm8Ofk6Njp0OrI67zstO2s7qjvoPCc8ZTykPOM9Ij1hPaE94D4gPmA%2BoD7gPyE/YT%2BiP%2BJAI0BkQKZA50EpQWpBrEHuQjBCckK1QvdDOkN9Q8BEA0RHRIpEzkUSRVVFmkXeRiJGZ0arRvBHNUd7R8BIBUhLSJFI10kdSWNJqUnwSjdKfUrESwxLU0uaS%2BJMKkxyTLpNAk1KTZNN3E4lTm5Ot08AT0lPk0/dUCdQcVC7UQZRUFGbUeZSMVJ8UsdTE1NfU6pT9lRCVI9U21UoVXVVwlYPVlxWqVb3V0RXklfgWC9YfVjLWRpZaVm4WgdaVlqmWvVbRVuVW%2BVcNVyGXNZdJ114XcleGl5sXr1fD19hX7NgBWBXYKpg/GFPYaJh9WJJYpxi8GNDY5dj62RAZJRk6WU9ZZJl52Y9ZpJm6Gc9Z5Nn6Wg/aJZo7GlDaZpp8WpIap9q92tPa6dr/2xXbK9tCG1gbbluEm5rbsRvHm94b9FwK3CGcOBxOnGVcfByS3KmcwFzXXO4dBR0cHTMdSh1hXXhdj52m3b4d1Z3s3gReG54zHkqeYl553pGeqV7BHtje8J8IXyBfOF9QX2hfgF%2BYn7CfyN/hH/lgEeAqIEKgWuBzYIwgpKC9INXg7qEHYSAhOOFR4Wrhg6GcobXhzuHn4gEiGmIzokziZmJ/opkisqLMIuWi/yMY4zKjTGNmI3/jmaOzo82j56QBpBukNaRP5GokhGSepLjk02TtpQglIqU9JVflcmWNJaflwqXdZfgmEyYuJkkmZCZ/JpomtWbQpuvnByciZz3nWSd0p5Anq6fHZ%2BLn/qgaaDYoUehtqImopajBqN2o%2BakVqTHpTilqaYapoum/adup%2BCoUqjEqTepqaocqo%2BrAqt1q%2BmsXKzQrUStuK4trqGvFq%2BLsACwdbDqsWCx1rJLssKzOLOutCW0nLUTtYq2AbZ5tvC3aLfguFm40blKucK6O7q1uy67p7whvJu9Fb2Pvgq%2BhL7/v3q/9cBwwOzBZ8Hjwl/C28NYw9TEUcTOxUvFyMZGxsPHQce/yD3IvMk6ybnKOMq3yzbLtsw1zLXNNc21zjbOts83z7jQOdC60TzRvtI/0sHTRNPG1EnUy9VO1dHWVdbY11zX4Nhk2OjZbNnx2nba%2B9uA3AXcit0Q3ZbeHN6i3ynfr%2BA24L3hROHM4lPi2%2BNj4%2Bvkc%2BT85YTmDeaW5x/nqegy6LzpRunQ6lvq5etw6/vshu0R7ZzuKO6070DvzPBY8OXxcvH/8ozzGfOn9DT0wvVQ9d72bfb794r4Gfio%2BTj5x/pX%2Buf7d/wH/Jj9Kf26/kv%2B3P9t////2wBDAAcFBQYFBAcGBgYIBwcICxILCwoKCxYPEA0SGhYbGhkWGRgcICgiHB4mHhgZIzAkJiorLS4tGyIyNTEsNSgsLSz/2wBDAQcICAsJCxULCxUsHRkdLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCz/wAARCABCAGQDAREAAhEBAxEB/8QAHAAAAgMBAQEBAAAAAAAAAAAABAYDBQcCAQgA/8QAORAAAQMCBAQDBgQFBQEAAAAAAQIDBAURAAYSIRMxQVEiYXEHFDKBkcEVI0KhFmKCsfBDRFJy0ZL/xAAaAQADAQEBAQAAAAAAAAAAAAABAgMEBQAG/8QALxEAAgIBBAEBBgUFAQAAAAAAAQIAEQMEEiExQRMUIjJCUZEFI2GhsRVxgeHw8f/aAAwDAQACEQMRAD8AcsrUhuiUFXuoHEULyJrgskfyp6nHyoNLa/eBRxxLOA0GI34lOfdRCiK4ydSQNaum3Unph8JVB6jjgfzGBoGZ1m/M5nSzUai8GWwdLDRVskfc98c1smXWZeOZPljF1OfJ9HhOMNyo0FiX4lPNoWVujoNWnYeQx3dPhXGu1e/M1J%2BWOpVPVxCFodny3Usq3ulhV1D1UBjRXgCP6tdy2i%2B0ihREFLTEh64tc2Bwhxse4w1Cr0IpZjrEGsOreYS6yD%2BgpBt874qgI4kzl3nqUAWCixw5E9LCPmZuNQVwmmAHtXxkbWwgwtv33IEcyWi5gVTqhGlNucOQk31JFknyPbHsmPddcRCsY5tci1vMvv8AU4DYcsElQSAojue588R5qiYOZHWqe0mlyHISCpDzyQy9qHhA6HqMBaXxPUQbhLFdECO2zUWveZOkFThuq%2B2CrhuZUPQ6n0a3DVLCnqg62mKwLkAWaTboB/xHU9cY1x%2Bqbc0o%2B3/n8w98mI%2BaMzJqbmhrUmCwTw0q2Liuqzjm58x1DDHi6/7kydHIdqzFqnmpmVNdROpZeU0tSdniggX26Eftju4NGmBKU8x/TqfmpMCqxSgB2OlvdLby%2BIkfOwAw7KUNiUCMRW6WyM05ijUxa/eob8Vj8s8UItbsBYY8FuU3ZAIqIfpbz7rkynoeW4dV2XdFvQDbFSGkdw%2BZZBUWmH3QYDYYbAtw1Gx%2Bp54Kmu4S6noVKt1LjJIWkpVbkRincIMustU2A5D99dd1OJVZTSxsb9sY9TlcNsEg13UIXl4QpzMhDiJLZcKuGkbADe18FsjMu3qAnxOpldTVaozHVALJcVw0LSfET0wMWAqptrhAFSch%2BKoxpAOk8sAGenN5rPhYXqb5i4vg7VPJEFTfs9ZwiiGttDoYpUfYaebyhyA7%2BQxyNZqDqXGDAOP5/wBQk7uBMlerlUlwpr0yIuE3qCY7arDwc7qPc/t9Selh0S4UCjk%2BTNuIHEvIiJUZDT8sLBC3Cn8xSeRP3xvANVEbu5CiUtKSkbtdU3tfCkQEmuITmWDES/DkUp/jR5jQXwQbqZXyUkj15HFhSiQVi3cERl2plClGMbJGrnfE/XToGHeBBAXG1aUrUOlhhzzBuuNELLlUfp6eNFUFKV4EuEbj/qeuJkDxH2N2IDITKguOMMLbKmtigWVoP%2Bd8SKAm2kyKMjj5llxqauCptCklWsFQN0K7jFvTBEQrZuTU%2BvtonPPy4jKeKgpLiW/EhRFtQwShqrgrwIdTJlQzA4llUdC2G0hK3L20JH6iT0FsZ8gVO5ZELttWN0CGW4iUw0MqZ6OPN6lOfzeQ7DtjGT9Z00xhRQEzqvZ1k5izAxJkktQmHQpthJ2SAeZ7m2N%2Bl0S6dOOSezOalKZfVjP7L84te4NyIYA2dG6vMY0jHxNb57NeIvzqvRnxICaaqOpYBZU258B8x2wwSpnZwepDCp8uWy6thC3UteJVh0xBmAPMgchlnlnMCaBUVF1pK2nElBJG6PMYDrvWp5CVYMJ5SqnVHK/IVDSp1kkuLbJvZPkT64RsC7f1nnom67jMKfAg181d1kBZN22TulJtzPn/AGwm5q2zXjxBRuaDV7OMyqPKgURK48dQLZWjxOvX57jkk25Dyw29cYsyT5CxlZS8h1%2BoOgxqdIFjfiLUEAfM4zvr8Y8yUeKH7Jag4%2Bl%2BbMYC%2BqWGQ6f/AKUNIxgfW7hSA/8Af2nqMbanRKW3ATEm8J5pAsEaUqH7C1/S%2BOerOjbgaMBMS5NFgMFcGnNqj%2B8KStxKbbpHQ%2BXljq4sz5OW5qaNNvJKjqNkGAyiKlOkbbcrYBJudgAVEVfsbiiE3x41XiSAnxrDetsn0t98X/qGUHwR9p89Z8iLWZcjTYTQlJnxXWWUhsIcBacIHLY3ufnjXi16uaYEfvG3AxIkoUgp1DSoqsQemOgpDdQnqOWUqy7AmMxVrPBc8IttZXTftjHlSwWHclQJsypmMu1Gc9NfCWluKJCUbAD0wUdVG0StgmM%2BX6Z%2BGRUzDZx%2BSLNIB5Dqo/5thHfdwJqxIOGhL0d2p1lqE7LbYjSAEB5KVLsCbEgD0tiO4ILE9lYk0JruTsjULL1PK7hx9W3FcQFuOW3uhPQfX745moY5jbcCZyAJ7X860KhrKHJUZLqf0LVx3B/Sk2GILjLfAtxS0T5XtSNReEansSpbjhslOnY/0iw%2BoOK%2BzZm%2BKhANzGhKB3NtUn1IQ40ZpctZ0BSl8TT9Ntvpii6FQNzmWTAbpo80TK7sKMVvrEmQ74nFq/Uf/MEuBwooTsY8IQUJftxLIACSPTC3LVGyRmyHSae9Lm1NoNIF7KYWlRPQAEbnGrDqbu2B/wAf6nz1/rMDzhmaVm6pqkSAhbY8LTIbOlA%2Bg388KBzuEQkmIVZokcthxbvCWDYJTvfG/DmYcT1yOKwEhLbDZUq1u5x5yW%2BKJcZqRlZ2ch%2BTJKkxojZdkLSCUtoAvue/YdcSLVwsZRfcJejsuyYTkiQYkSQ0C22kXWli%2BxIHLVa4Bt0N7HBckcCaHfwIZWM30aM3HaoNJ4DMWwu64VcWxvdY5X58u%2BJBGbgye81UX6vnusVcLS/UFobVzaYOkK9SOfzwyaVV5r7xItNzm1ydK2TbvfceeNXpUO4dsY6dUE%2B5s0qkJPvs3wvyXDpIBPwJ7C3M8ziLL8zdCbMdKNq9mPlNpdHyZGS5NkN%2B8qF1LV8R8gOdsZCz5Tx1Nf5eEe8eZxVfaiosKapMNXh/13bAD5f%2B4Kabn3pnya8njGIsfxfmOoLU83WCkX02aWEpHyHrjR6KrxUzernfm4LWc4VqvPpcqdaWsI%2BFAIAT6ADEggHQuQ58yvXVUtI%2BJ11RHNSsMuNiYDBWYz02QlyQrhtr3F%2BvpjSAFEHYjFBZp8JSTLUtiMN1Buxdc8hfliTNfU8BCswe0NdTo38OUyMzSqJcF1trxOPWN/ErmokgcsOilfePcpdRc4s2UC1CpMp1BFgoIUST0vty%2BeEvGvLsItzleXMySGwHKG9oPdq3998e9qwL00O79ISjJFWH5ooTiEpTcgu8/wDO2Pe3Yj5gu4JMoNUdWkLgmOhAsLNEfU9cOuoxt0YQwEjiRkQZCVXdMhO6VBBGk%2BV9v74ctuFRwWPXEYaBWsrNuOP14PvySfhcQpe/qFb/ADGIZMeT5JbF6Q5ycmV%2Bec4pnOO0akllNJSUk8NoJLihv9Ae1sV0%2BCvffuHPlB9xOovUyuS6bFU1H4OhSys62wo3sB9saGxhjZkFyFRQmiVD2POwllTK3duWtOoftjiD8QyfOshZgdG9n1QlVZMYobeeUfCFLCE%2BpJxsw50y8DuAmahC9hkyQwk1GSzpP6W97ehxpbFmb4aEIsdS4jexLL0NSVSGVSFDq8oq/Ym37YT2XL8z/aE7pfuezqlxIhNMjsocTsUobA3%2BQxLL%2BHqVtSSYCp%2Bsr/4PqbgIHDbB6qUB98cz2B76qH03M5dyg60j86oxmwPO/wBsTbTbe2E8cddmCtZcZSs2rLar8wloq%2B%2BAMdef2g2D6yVWU4Ck3cmSVA7kpZ0j98N6XNz2xfrE/M0BiLI93jyBo2I1rSVfQY0Y0C8z1gRVrmR2qmlyot7qCAVGxsD52xrxZCvu1BuI4mbS6dwZTjK4oUpBsSkKscbgzRyZH%2BHkf7RQ%2BSsNuaesz7TrLTYBPDTfT2xzdSoBNCVcCpmmZWm0q1BCQruBvjkvM7R99l0h5%2BguB15xwJVZIUom3pj6L8OYti5MKx2UkHcgEjHSjwGetaWjZSh6HGDVsQnBlfETp7zplBJcXa/LUccMGzzIkmWqWGUwtaWkBdviCRfGmgFsRq4i/Kfe45HFXbtqOMLMb7iQYJC06lAKPc74METc2oSKq0QkAkc7Y1Y%2BhFPcDnOLRSjpWpO3Q2xX5oWmJVyZK/FXh7y98R/WcdVBxKDqVRfdUbl1ZPmo4pQhn//Z)
