# Journey to Passwordless

## Windows Hello for Business
[Windows Hello for Business](https://learn.microsoft.com/en-us/windows/security/identity-protection/hello-for-business/hello-identity-verification)

![Windows Hello for Business with Hybrid Azure AD Join Visual](Images/auth-haadj-keytrust.png)

[How Windows Hellow for Business Works](https://learn.microsoft.com/en-us/windows/security/identity-protection/hello-for-business/hello-how-it-works-authentication)


## Seamless SSO
[Azure Seamless SSO](https://learn.microsoft.com/en-us/azure/active-directory/hybrid/connect/how-to-connect-sso)


## Conditional Access MFA
[Azure Conditional Access](https://learn.microsoft.com/en-us/azure/active-directory/conditional-access/howto-conditional-access-policy-all-users-mfa)


## Certificate Based Authentication
[VPN or Wireless Authentintication](https://learn.microsoft.com/en-us/mem/intune/configuration/wi-fi-settings-configure)

## Azure Application Proxy
[SSO without VPN](https://learn.microsoft.com/en-us/azure/active-directory/app-proxy/application-proxy)

## Azure AD Custom Branding
[Add Custom Branding to Sign-on Page](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/how-to-customize-branding)

![](Images/azureappproxxy.png)

## Complex Password without Experation Policy

[NIST Recommendation](https://pages.nist.gov/800-63-FAQ/#q-b05)

## Benifits

- Better user experiance
- Less support tickets
- Passwords more secure
  - Tougher to crack
- Almost phish resistant
  - Use many times do not know what their password is


## What it Does Not Help With

- Traditional Red Team tools - Mimikatz
  - Credentials can be secured using [Credential Guard](https://learn.microsoft.com/en-us/windows/security/identity-protection/remote-credential-guard)
- Legacy systems that do not support modern auth (i.e. NTLM)


## QR Code for Resources

![](Images/frame-2.png)