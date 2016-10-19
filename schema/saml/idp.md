# SAML IDP

## Non-normative example of a SAML IDP entry

```
{
    "@id": "https://ra.org/federation_entity/d8e89c32-325f-40c5-ab79-eabd6b27b4ae",
    "@context": "https://kantarainitiative.org/otto/schema/saml_idp.json",
    "name": "Acme Incorporated IDP",  
    "entity_asserted_metadata": "PEVudGl0eURlc2NyaXB0b3IgeG1sbnM9InVybjpvYXNpczpuYW1lczp0YzpTQU1MOjIuMDptZXRhZGF0YSIgeG1sbnM6ZHM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvMDkveG1sZHNpZyMiIHhtbG5zOnNoaWJtZD0idXJuOm1hY2U6c2hpYmJvbGV0aDptZXRhZGF0YToxLjAiIHhtbG5zOnhzaT0iaHR0cDovL3d3dy53My5vcmcvMjAwMS9YTUxTY2hlbWEtaW5zdGFuY2UiIGVudGl0eUlEPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1L2lkcC9zaGliYm9sZXRoIj4NCjxJRFBTU09EZXNjcmlwdG9yIGVycm9yVVJMPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1L2lkZW50aXR5L2ZlZWRiYWNrLmh0bSIgcHJvdG9jb2xTdXBwb3J0RW51bWVyYXRpb249InVybjptYWNlOnNoaWJib2xldGg6MS4wIHVybjpvYXNpczpuYW1lczp0YzpTQU1MOjEuMTpwcm90b2NvbCB1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6cHJvdG9jb2wiPg0KPEV4dGVuc2lvbnM+DQo8c2hpYm1kOlNjb3BlIHJlZ2V4cD0iZmFsc2UiPmlkcC5taWxsZXJzdmlsbGUuZWR1PC9zaGlibWQ6U2NvcGU+DQo8L0V4dGVuc2lvbnM+DQo8S2V5RGVzY3JpcHRvcj4NCjxkczpLZXlJbmZvPg0KPGRzOlg1MDlEYXRhPg0KPGRzOlg1MDlDZXJ0aWZpY2F0ZT4NCk1JSUR2akNDQXFZQ0NRQ2FkOXdlSEltamZUQU5CZ2txaGtpRzl3MEJBUVVGQURDQm9ERUxNQWtHQTFVRUJoTUMgVlZNeEZUQVRCZ05WQkFnTURGQmxibTV6ZVd4MllXNXBZVEVWTUJNR0ExVUVCd3dNVFdsc2JHVnljM1pwYkd4bCBNUXN3Q1FZRFZRUUtEQUpOVlRFTE1Ba0dBMVVFQ3d3Q1NWUXhIVEFiQmdOVkJBTU1GR2xrY0M1dGFXeHNaWEp6IGRtbHNiR1V1WldSMU1Tb3dLQVlKS29aSWh2Y05BUWtCRmh0clpXbDBhQzUzWlc1NlFHMXBiR3hsY25OMmFXeHMgWlM1bFpIVXdIaGNOTVRRd01qRXlNakF6TkRVMldoY05NalF3TWpFeU1qQXpORFUyV2pDQm9ERUxNQWtHQTFVRSBCaE1DVlZNeEZUQVRCZ05WQkFnTURGQmxibTV6ZVd4MllXNXBZVEVWTUJNR0ExVUVCd3dNVFdsc2JHVnljM1pwIGJHeGxNUXN3Q1FZRFZRUUtEQUpOVlRFTE1Ba0dBMVVFQ3d3Q1NWUXhIVEFiQmdOVkJBTU1GR2xrY0M1dGFXeHMgWlhKemRtbHNiR1V1WldSMU1Tb3dLQVlKS29aSWh2Y05BUWtCRmh0clpXbDBhQzUzWlc1NlFHMXBiR3hsY25OMiBhV3hzWlM1bFpIVXdnZ0VpTUEwR0NTcUdTSWIzRFFFQkFRVUFBNElCRHdBd2dnRUtBb0lCQVFEY3hvM1hKeUo0IFhGRWJjRnhpMnRMYmVZa2dUcGtDYTVTa0o1aVJYSjFuelkzUXh0TGRVbERQU0RaOHlMMC9hSG1Pck5ZeWJsVHUgeVMrN0FXR09OcFVjTzRUQytvL3dYUlgyYkEzNTF3cVAyakIrZXBabUplVCtzR1J3ZHdENFp6OExzRUxsY0k3OSBLd3plZlZQRTk5cTBseWVXcjhBWEs2dVczdlY1eThha0htVmNyakJ4bGgzNmluQ3dPZ1RRU2x2WXRiWEhjaVZQIEIwL3RTTUdHOHBOaEthQ0RoTzlnOEdDd0phWk9HbEE5WHl6NDJObCthK2F6akx6blZNcGdXYndZM1lFWjNqdSsganhuSW1RaEtVTGpUK2FZMFBOazYreis3TkRlRkVGZkEvQi9RMlFYVVI2NHNWY1A1bFJOekljVis1Nm1KQWJrTSB2d1M3Q0Y1bDlGSnhBZ01CQUFFd0RRWUpLb1pJaHZjTkFRRUZCUUFEZ2dFQkFKWllGYWhpRGUyZHpRSVJBMWpTIGppblI3MGJUemtpT25RTm5HUWVMaTFzb01zaXgrNSt0bFVOeDUxL2tIZXZqRW1JWGFGLzFFeGRKTUE3V2dJcmIgV1RrdVpaNFZhdmZqMlI2Sm9OV3UyRlJXLzJNMURyWEpxcGJ3VUdjWGpkSFEycmJCWW1Wd1NDYXRORlRzU0hpcCBsTDJIUFFaR3ZodDQyaUFFYmsvVi8xeXJrM29MMmdNQ1FORTcyTFpzUitOc0J3eHFJQ3E4Vk1BNE1oUmxtS2o5IFc5ZjQ5WkV0UGVDc0lSbEJqNStnOGJwMEtwLzAxK1pCc1VIM3N6NElsN3hkS1A1U0RtU2xpd3NkdEZkdEd0RzMgQjFIcjg1eHRxVHRJL21ieG1mY2RjbW1mclk1TWVNc2kzRlduMjUrbjl2b3VEQXJSOUNQQnN3bmFDN1FRdjhRNSBYYVk9DQo8L2RzOlg1MDlDZXJ0aWZpY2F0ZT4NCjwvZHM6WDUwOURhdGE+DQo8L2RzOktleUluZm8+DQo8L0tleURlc2NyaXB0b3I+DQo8QXJ0aWZhY3RSZXNvbHV0aW9uU2VydmljZSBCaW5kaW5nPSJ1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoxLjA6YmluZGluZ3M6U09BUC1iaW5kaW5nIiBMb2NhdGlvbj0iaHR0cHM6Ly9pZHAubWlsbGVyc3ZpbGxlLmVkdTo5NDQzL2lkcC9wcm9maWxlL1NBTUwxL1NPQVAvQXJ0aWZhY3RSZXNvbHV0aW9uIiBpbmRleD0iMSIvPg0KPEFydGlmYWN0UmVzb2x1dGlvblNlcnZpY2UgQmluZGluZz0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOmJpbmRpbmdzOlNPQVAiIExvY2F0aW9uPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1Ojk0NDMvaWRwL3Byb2ZpbGUvU0FNTDIvU09BUC9BcnRpZmFjdFJlc29sdXRpb24iIGluZGV4PSIyIi8+DQo8TmFtZUlERm9ybWF0PnVybjptYWNlOnNoaWJib2xldGg6MS4wOm5hbWVJZGVudGlmaWVyPC9OYW1lSURGb3JtYXQ+DQo8TmFtZUlERm9ybWF0Pg0KdXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOm5hbWVpZC1mb3JtYXQ6dHJhbnNpZW50DQo8L05hbWVJREZvcm1hdD4NCjxOYW1lSURGb3JtYXQ+DQp1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6bmFtZWlkLWZvcm1hdDpwZXJzaXN0ZW50DQo8L05hbWVJREZvcm1hdD4NCjxTaW5nbGVTaWduT25TZXJ2aWNlIEJpbmRpbmc9InVybjptYWNlOnNoaWJib2xldGg6MS4wOnByb2ZpbGVzOkF1dGhuUmVxdWVzdCIgTG9jYXRpb249Imh0dHBzOi8vaWRwLm1pbGxlcnN2aWxsZS5lZHUvaWRwL3Byb2ZpbGUvU2hpYmJvbGV0aC9TU08iLz4NCjxTaW5nbGVTaWduT25TZXJ2aWNlIEJpbmRpbmc9InVybjptYWNlOnNoaWJib2xldGg6Mi4wOnByb2ZpbGVzOkF1dGhuUmVxdWVzdCIgTG9jYXRpb249Imh0dHBzOi8vaWRwLm1pbGxlcnN2aWxsZS5lZHUvaWRwL3Byb2ZpbGUvU0FNTDIvVW5zb2xpY2l0ZWQvU1NPIi8+DQo8U2luZ2xlU2lnbk9uU2VydmljZSBCaW5kaW5nPSJ1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6YmluZGluZ3M6SFRUUC1QT1NUIiBMb2NhdGlvbj0iaHR0cHM6Ly9pZHAubWlsbGVyc3ZpbGxlLmVkdS9pZHAvcHJvZmlsZS9TQU1MMi9QT1NUL1NTTyIvPg0KPFNpbmdsZVNpZ25PblNlcnZpY2UgQmluZGluZz0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOmJpbmRpbmdzOkhUVFAtUE9TVC1TaW1wbGVTaWduIiBMb2NhdGlvbj0iaHR0cHM6Ly9pZHAubWlsbGVyc3ZpbGxlLmVkdS9pZHAvcHJvZmlsZS9TQU1MMi9QT1NULVNpbXBsZVNpZ24vU1NPIi8+DQo8U2luZ2xlU2lnbk9uU2VydmljZSBCaW5kaW5nPSJ1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6YmluZGluZ3M6SFRUUC1SZWRpcmVjdCIgTG9jYXRpb249Imh0dHBzOi8vaWRwLm1pbGxlcnN2aWxsZS5lZHUvaWRwL3Byb2ZpbGUvU0FNTDIvUmVkaXJlY3QvU1NPIi8+DQo8L0lEUFNTT0Rlc2NyaXB0b3I+DQo8QXR0cmlidXRlQXV0aG9yaXR5RGVzY3JpcHRvciBwcm90b2NvbFN1cHBvcnRFbnVtZXJhdGlvbj0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6MS4xOnByb3RvY29sIHVybjpvYXNpczpuYW1lczp0YzpTQU1MOjIuMDpwcm90b2NvbCI+DQo8RXh0ZW5zaW9ucz4NCjxzaGlibWQ6U2NvcGUgcmVnZXhwPSJmYWxzZSI+aWRwLm1pbGxlcnN2aWxsZS5lZHU8L3NoaWJtZDpTY29wZT4NCjwvRXh0ZW5zaW9ucz4NCjxLZXlEZXNjcmlwdG9yPg0KPGRzOktleUluZm8+DQo8ZHM6WDUwOURhdGE+DQo8ZHM6WDUwOUNlcnRpZmljYXRlPg0KTUlJRHZqQ0NBcVlDQ1FDYWQ5d2VISW1qZlRBTkJna3Foa2lHOXcwQkFRVUZBRENCb0RFTE1Ba0dBMVVFQmhNQyBWVk14RlRBVEJnTlZCQWdNREZCbGJtNXplV3gyWVc1cFlURVZNQk1HQTFVRUJ3d01UV2xzYkdWeWMzWnBiR3hsIE1Rc3dDUVlEVlFRS0RBSk5WVEVMTUFrR0ExVUVDd3dDU1ZReEhUQWJCZ05WQkFNTUZHbGtjQzV0YVd4c1pYSnogZG1sc2JHVXVaV1IxTVNvd0tBWUpLb1pJaHZjTkFRa0JGaHRyWldsMGFDNTNaVzU2UUcxcGJHeGxjbk4yYVd4cyBaUzVsWkhVd0hoY05NVFF3TWpFeU1qQXpORFUyV2hjTk1qUXdNakV5TWpBek5EVTJXakNCb0RFTE1Ba0dBMVVFIEJoTUNWVk14RlRBVEJnTlZCQWdNREZCbGJtNXplV3gyWVc1cFlURVZNQk1HQTFVRUJ3d01UV2xzYkdWeWMzWnAgYkd4bE1Rc3dDUVlEVlFRS0RBSk5WVEVMTUFrR0ExVUVDd3dDU1ZReEhUQWJCZ05WQkFNTUZHbGtjQzV0YVd4cyBaWEp6ZG1sc2JHVXVaV1IxTVNvd0tBWUpLb1pJaHZjTkFRa0JGaHRyWldsMGFDNTNaVzU2UUcxcGJHeGxjbk4yIGFXeHNaUzVsWkhVd2dnRWlNQTBHQ1NxR1NJYjNEUUVCQVFVQUE0SUJEd0F3Z2dFS0FvSUJBUURjeG8zWEp5SjQgWEZFYmNGeGkydExiZVlrZ1Rwa0NhNVNrSjVpUlhKMW56WTNReHRMZFVsRFBTRFo4eUwwL2FIbU9yTll5YmxUdSB5Uys3QVdHT05wVWNPNFRDK28vd1hSWDJiQTM1MXdxUDJqQitlcFptSmVUK3NHUndkd0Q0Wno4THNFTGxjSTc5IEt3emVmVlBFOTlxMGx5ZVdyOEFYSzZ1VzN2VjV5OGFrSG1WY3JqQnhsaDM2aW5Dd09nVFFTbHZZdGJYSGNpVlAgQjAvdFNNR0c4cE5oS2FDRGhPOWc4R0N3SmFaT0dsQTlYeXo0Mk5sK2ErYXpqTHpuVk1wZ1did1kzWUVaM2p1KyBqeG5JbVFoS1VMalQrYVkwUE5rNit6KzdORGVGRUZmQS9CL1EyUVhVUjY0c1ZjUDVsUk56SWNWKzU2bUpBYmtNIHZ3UzdDRjVsOUZKeEFnTUJBQUV3RFFZSktvWklodmNOQVFFRkJRQURnZ0VCQUpaWUZhaGlEZTJkelFJUkExalMgamluUjcwYlR6a2lPblFObkdRZUxpMXNvTXNpeCs1K3RsVU54NTEva0hldmpFbUlYYUYvMUV4ZEpNQTdXZ0lyYiBXVGt1Wlo0VmF2ZmoyUjZKb05XdTJGUlcvMk0xRHJYSnFwYndVR2NYamRIUTJyYkJZbVZ3U0NhdE5GVHNTSGlwIGxMMkhQUVpHdmh0NDJpQUViay9WLzF5cmszb0wyZ01DUU5FNzJMWnNSK05zQnd4cUlDcThWTUE0TWhSbG1LajkgVzlmNDlaRXRQZUNzSVJsQmo1K2c4YnAwS3AvMDErWkJzVUgzc3o0SWw3eGRLUDVTRG1TbGl3c2R0RmR0R3RHMyBCMUhyODV4dHFUdEkvbWJ4bWZjZGNtbWZyWTVNZU1zaTNGV24yNStuOXZvdURBclI5Q1BCc3duYUM3UVF2OFE1IFhhWT0NCjwvZHM6WDUwOUNlcnRpZmljYXRlPg0KPC9kczpYNTA5RGF0YT4NCjwvZHM6S2V5SW5mbz4NCjwvS2V5RGVzY3JpcHRvcj4NCjxBdHRyaWJ1dGVTZXJ2aWNlIEJpbmRpbmc9InVybjpvYXNpczpuYW1lczp0YzpTQU1MOjEuMDpiaW5kaW5nczpTT0FQLWJpbmRpbmciIExvY2F0aW9uPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1Ojk0NDMvaWRwL3Byb2ZpbGUvU0FNTDEvU09BUC9BdHRyaWJ1dGVRdWVyeSIvPg0KPEF0dHJpYnV0ZVNlcnZpY2UgQmluZGluZz0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOmJpbmRpbmdzOlNPQVAiIExvY2F0aW9uPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1Ojk0NDMvaWRwL3Byb2ZpbGUvU0FNTDIvU09BUC9BdHRyaWJ1dGVRdWVyeSIvPg0KPE5hbWVJREZvcm1hdD51cm46bWFjZTpzaGliYm9sZXRoOjEuMDpuYW1lSWRlbnRpZmllcjwvTmFtZUlERm9ybWF0Pg0KPE5hbWVJREZvcm1hdD4NCnVybjpvYXNpczpuYW1lczp0YzpTQU1MOjIuMDpuYW1laWQtZm9ybWF0OnRyYW5zaWVudA0KPC9OYW1lSURGb3JtYXQ+DQo8TmFtZUlERm9ybWF0Pg0KdXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOm5hbWVpZC1mb3JtYXQ6cGVyc2lzdGVudA0KPC9OYW1lSURGb3JtYXQ+DQo8L0F0dHJpYnV0ZUF1dGhvcml0eURlc2NyaXB0b3I+DQo8L0VudGl0eURlc2NyaXB0b3I+",
    "federation_asserted_metadata": "PEVudGl0eURlc2NyaXB0b3IgeG1sbnM9InVybjpvYXNpczpuYW1lczp0YzpTQU1MOjIuMDptZXRhZGF0YSIgeG1sbnM6ZHM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvMDkveG1sZHNpZyMiIHhtbG5zOnNoaWJtZD0idXJuOm1hY2U6c2hpYmJvbGV0aDptZXRhZGF0YToxLjAiIHhtbG5zOnhzaT0iaHR0cDovL3d3dy53My5vcmcvMjAwMS9YTUxTY2hlbWEtaW5zdGFuY2UiIGVudGl0eUlEPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1L2lkcC9zaGliYm9sZXRoIj4NCjxJRFBTU09EZXNjcmlwdG9yIGVycm9yVVJMPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1L2lkZW50aXR5L2ZlZWRiYWNrLmh0bSIgcHJvdG9jb2xTdXBwb3J0RW51bWVyYXRpb249InVybjptYWNlOnNoaWJib2xldGg6MS4wIHVybjpvYXNpczpuYW1lczp0YzpTQU1MOjEuMTpwcm90b2NvbCB1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6cHJvdG9jb2wiPg0KPEV4dGVuc2lvbnM+DQo8c2hpYm1kOlNjb3BlIHJlZ2V4cD0iZmFsc2UiPmlkcC5taWxsZXJzdmlsbGUuZWR1PC9zaGlibWQ6U2NvcGU+DQo8L0V4dGVuc2lvbnM+DQo8S2V5RGVzY3JpcHRvcj4NCjxkczpLZXlJbmZvPg0KPGRzOlg1MDlEYXRhPg0KPGRzOlg1MDlDZXJ0aWZpY2F0ZT4NCk1JSUR2akNDQXFZQ0NRQ2FkOXdlSEltamZUQU5CZ2txaGtpRzl3MEJBUVVGQURDQm9ERUxNQWtHQTFVRUJoTUMgVlZNeEZUQVRCZ05WQkFnTURGQmxibTV6ZVd4MllXNXBZVEVWTUJNR0ExVUVCd3dNVFdsc2JHVnljM1pwYkd4bCBNUXN3Q1FZRFZRUUtEQUpOVlRFTE1Ba0dBMVVFQ3d3Q1NWUXhIVEFiQmdOVkJBTU1GR2xrY0M1dGFXeHNaWEp6IGRtbHNiR1V1WldSMU1Tb3dLQVlKS29aSWh2Y05BUWtCRmh0clpXbDBhQzUzWlc1NlFHMXBiR3hsY25OMmFXeHMgWlM1bFpIVXdIaGNOTVRRd01qRXlNakF6TkRVMldoY05NalF3TWpFeU1qQXpORFUyV2pDQm9ERUxNQWtHQTFVRSBCaE1DVlZNeEZUQVRCZ05WQkFnTURGQmxibTV6ZVd4MllXNXBZVEVWTUJNR0ExVUVCd3dNVFdsc2JHVnljM1pwIGJHeGxNUXN3Q1FZRFZRUUtEQUpOVlRFTE1Ba0dBMVVFQ3d3Q1NWUXhIVEFiQmdOVkJBTU1GR2xrY0M1dGFXeHMgWlhKemRtbHNiR1V1WldSMU1Tb3dLQVlKS29aSWh2Y05BUWtCRmh0clpXbDBhQzUzWlc1NlFHMXBiR3hsY25OMiBhV3hzWlM1bFpIVXdnZ0VpTUEwR0NTcUdTSWIzRFFFQkFRVUFBNElCRHdBd2dnRUtBb0lCQVFEY3hvM1hKeUo0IFhGRWJjRnhpMnRMYmVZa2dUcGtDYTVTa0o1aVJYSjFuelkzUXh0TGRVbERQU0RaOHlMMC9hSG1Pck5ZeWJsVHUgeVMrN0FXR09OcFVjTzRUQytvL3dYUlgyYkEzNTF3cVAyakIrZXBabUplVCtzR1J3ZHdENFp6OExzRUxsY0k3OSBLd3plZlZQRTk5cTBseWVXcjhBWEs2dVczdlY1eThha0htVmNyakJ4bGgzNmluQ3dPZ1RRU2x2WXRiWEhjaVZQIEIwL3RTTUdHOHBOaEthQ0RoTzlnOEdDd0phWk9HbEE5WHl6NDJObCthK2F6akx6blZNcGdXYndZM1lFWjNqdSsganhuSW1RaEtVTGpUK2FZMFBOazYreis3TkRlRkVGZkEvQi9RMlFYVVI2NHNWY1A1bFJOekljVis1Nm1KQWJrTSB2d1M3Q0Y1bDlGSnhBZ01CQUFFd0RRWUpLb1pJaHZjTkFRRUZCUUFEZ2dFQkFKWllGYWhpRGUyZHpRSVJBMWpTIGppblI3MGJUemtpT25RTm5HUWVMaTFzb01zaXgrNSt0bFVOeDUxL2tIZXZqRW1JWGFGLzFFeGRKTUE3V2dJcmIgV1RrdVpaNFZhdmZqMlI2Sm9OV3UyRlJXLzJNMURyWEpxcGJ3VUdjWGpkSFEycmJCWW1Wd1NDYXRORlRzU0hpcCBsTDJIUFFaR3ZodDQyaUFFYmsvVi8xeXJrM29MMmdNQ1FORTcyTFpzUitOc0J3eHFJQ3E4Vk1BNE1oUmxtS2o5IFc5ZjQ5WkV0UGVDc0lSbEJqNStnOGJwMEtwLzAxK1pCc1VIM3N6NElsN3hkS1A1U0RtU2xpd3NkdEZkdEd0RzMgQjFIcjg1eHRxVHRJL21ieG1mY2RjbW1mclk1TWVNc2kzRlduMjUrbjl2b3VEQXJSOUNQQnN3bmFDN1FRdjhRNSBYYVk9DQo8L2RzOlg1MDlDZXJ0aWZpY2F0ZT4NCjwvZHM6WDUwOURhdGE+DQo8L2RzOktleUluZm8+DQo8L0tleURlc2NyaXB0b3I+DQo8QXJ0aWZhY3RSZXNvbHV0aW9uU2VydmljZSBCaW5kaW5nPSJ1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoxLjA6YmluZGluZ3M6U09BUC1iaW5kaW5nIiBMb2NhdGlvbj0iaHR0cHM6Ly9pZHAubWlsbGVyc3ZpbGxlLmVkdTo5NDQzL2lkcC9wcm9maWxlL1NBTUwxL1NPQVAvQXJ0aWZhY3RSZXNvbHV0aW9uIiBpbmRleD0iMSIvPg0KPEFydGlmYWN0UmVzb2x1dGlvblNlcnZpY2UgQmluZGluZz0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOmJpbmRpbmdzOlNPQVAiIExvY2F0aW9uPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1Ojk0NDMvaWRwL3Byb2ZpbGUvU0FNTDIvU09BUC9BcnRpZmFjdFJlc29sdXRpb24iIGluZGV4PSIyIi8+DQo8TmFtZUlERm9ybWF0PnVybjptYWNlOnNoaWJib2xldGg6MS4wOm5hbWVJZGVudGlmaWVyPC9OYW1lSURGb3JtYXQ+DQo8TmFtZUlERm9ybWF0Pg0KdXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOm5hbWVpZC1mb3JtYXQ6dHJhbnNpZW50DQo8L05hbWVJREZvcm1hdD4NCjxOYW1lSURGb3JtYXQ+DQp1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6bmFtZWlkLWZvcm1hdDpwZXJzaXN0ZW50DQo8L05hbWVJREZvcm1hdD4NCjxTaW5nbGVTaWduT25TZXJ2aWNlIEJpbmRpbmc9InVybjptYWNlOnNoaWJib2xldGg6MS4wOnByb2ZpbGVzOkF1dGhuUmVxdWVzdCIgTG9jYXRpb249Imh0dHBzOi8vaWRwLm1pbGxlcnN2aWxsZS5lZHUvaWRwL3Byb2ZpbGUvU2hpYmJvbGV0aC9TU08iLz4NCjxTaW5nbGVTaWduT25TZXJ2aWNlIEJpbmRpbmc9InVybjptYWNlOnNoaWJib2xldGg6Mi4wOnByb2ZpbGVzOkF1dGhuUmVxdWVzdCIgTG9jYXRpb249Imh0dHBzOi8vaWRwLm1pbGxlcnN2aWxsZS5lZHUvaWRwL3Byb2ZpbGUvU0FNTDIvVW5zb2xpY2l0ZWQvU1NPIi8+DQo8U2luZ2xlU2lnbk9uU2VydmljZSBCaW5kaW5nPSJ1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6YmluZGluZ3M6SFRUUC1QT1NUIiBMb2NhdGlvbj0iaHR0cHM6Ly9pZHAubWlsbGVyc3ZpbGxlLmVkdS9pZHAvcHJvZmlsZS9TQU1MMi9QT1NUL1NTTyIvPg0KPFNpbmdsZVNpZ25PblNlcnZpY2UgQmluZGluZz0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOmJpbmRpbmdzOkhUVFAtUE9TVC1TaW1wbGVTaWduIiBMb2NhdGlvbj0iaHR0cHM6Ly9pZHAubWlsbGVyc3ZpbGxlLmVkdS9pZHAvcHJvZmlsZS9TQU1MMi9QT1NULVNpbXBsZVNpZ24vU1NPIi8+DQo8U2luZ2xlU2lnbk9uU2VydmljZSBCaW5kaW5nPSJ1cm46b2FzaXM6bmFtZXM6dGM6U0FNTDoyLjA6YmluZGluZ3M6SFRUUC1SZWRpcmVjdCIgTG9jYXRpb249Imh0dHBzOi8vaWRwLm1pbGxlcnN2aWxsZS5lZHUvaWRwL3Byb2ZpbGUvU0FNTDIvUmVkaXJlY3QvU1NPIi8+DQo8L0lEUFNTT0Rlc2NyaXB0b3I+DQo8QXR0cmlidXRlQXV0aG9yaXR5RGVzY3JpcHRvciBwcm90b2NvbFN1cHBvcnRFbnVtZXJhdGlvbj0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6MS4xOnByb3RvY29sIHVybjpvYXNpczpuYW1lczp0YzpTQU1MOjIuMDpwcm90b2NvbCI+DQo8RXh0ZW5zaW9ucz4NCjxzaGlibWQ6U2NvcGUgcmVnZXhwPSJmYWxzZSI+aWRwLm1pbGxlcnN2aWxsZS5lZHU8L3NoaWJtZDpTY29wZT4NCjwvRXh0ZW5zaW9ucz4NCjxLZXlEZXNjcmlwdG9yPg0KPGRzOktleUluZm8+DQo8ZHM6WDUwOURhdGE+DQo8ZHM6WDUwOUNlcnRpZmljYXRlPg0KTUlJRHZqQ0NBcVlDQ1FDYWQ5d2VISW1qZlRBTkJna3Foa2lHOXcwQkFRVUZBRENCb0RFTE1Ba0dBMVVFQmhNQyBWVk14RlRBVEJnTlZCQWdNREZCbGJtNXplV3gyWVc1cFlURVZNQk1HQTFVRUJ3d01UV2xzYkdWeWMzWnBiR3hsIE1Rc3dDUVlEVlFRS0RBSk5WVEVMTUFrR0ExVUVDd3dDU1ZReEhUQWJCZ05WQkFNTUZHbGtjQzV0YVd4c1pYSnogZG1sc2JHVXVaV1IxTVNvd0tBWUpLb1pJaHZjTkFRa0JGaHRyWldsMGFDNTNaVzU2UUcxcGJHeGxjbk4yYVd4cyBaUzVsWkhVd0hoY05NVFF3TWpFeU1qQXpORFUyV2hjTk1qUXdNakV5TWpBek5EVTJXakNCb0RFTE1Ba0dBMVVFIEJoTUNWVk14RlRBVEJnTlZCQWdNREZCbGJtNXplV3gyWVc1cFlURVZNQk1HQTFVRUJ3d01UV2xzYkdWeWMzWnAgYkd4bE1Rc3dDUVlEVlFRS0RBSk5WVEVMTUFrR0ExVUVDd3dDU1ZReEhUQWJCZ05WQkFNTUZHbGtjQzV0YVd4cyBaWEp6ZG1sc2JHVXVaV1IxTVNvd0tBWUpLb1pJaHZjTkFRa0JGaHRyWldsMGFDNTNaVzU2UUcxcGJHeGxjbk4yIGFXeHNaUzVsWkhVd2dnRWlNQTBHQ1NxR1NJYjNEUUVCQVFVQUE0SUJEd0F3Z2dFS0FvSUJBUURjeG8zWEp5SjQgWEZFYmNGeGkydExiZVlrZ1Rwa0NhNVNrSjVpUlhKMW56WTNReHRMZFVsRFBTRFo4eUwwL2FIbU9yTll5YmxUdSB5Uys3QVdHT05wVWNPNFRDK28vd1hSWDJiQTM1MXdxUDJqQitlcFptSmVUK3NHUndkd0Q0Wno4THNFTGxjSTc5IEt3emVmVlBFOTlxMGx5ZVdyOEFYSzZ1VzN2VjV5OGFrSG1WY3JqQnhsaDM2aW5Dd09nVFFTbHZZdGJYSGNpVlAgQjAvdFNNR0c4cE5oS2FDRGhPOWc4R0N3SmFaT0dsQTlYeXo0Mk5sK2ErYXpqTHpuVk1wZ1did1kzWUVaM2p1KyBqeG5JbVFoS1VMalQrYVkwUE5rNit6KzdORGVGRUZmQS9CL1EyUVhVUjY0c1ZjUDVsUk56SWNWKzU2bUpBYmtNIHZ3UzdDRjVsOUZKeEFnTUJBQUV3RFFZSktvWklodmNOQVFFRkJRQURnZ0VCQUpaWUZhaGlEZTJkelFJUkExalMgamluUjcwYlR6a2lPblFObkdRZUxpMXNvTXNpeCs1K3RsVU54NTEva0hldmpFbUlYYUYvMUV4ZEpNQTdXZ0lyYiBXVGt1Wlo0VmF2ZmoyUjZKb05XdTJGUlcvMk0xRHJYSnFwYndVR2NYamRIUTJyYkJZbVZ3U0NhdE5GVHNTSGlwIGxMMkhQUVpHdmh0NDJpQUViay9WLzF5cmszb0wyZ01DUU5FNzJMWnNSK05zQnd4cUlDcThWTUE0TWhSbG1LajkgVzlmNDlaRXRQZUNzSVJsQmo1K2c4YnAwS3AvMDErWkJzVUgzc3o0SWw3eGRLUDVTRG1TbGl3c2R0RmR0R3RHMyBCMUhyODV4dHFUdEkvbWJ4bWZjZGNtbWZyWTVNZU1zaTNGV24yNStuOXZvdURBclI5Q1BCc3duYUM3UVF2OFE1IFhhWT0NCjwvZHM6WDUwOUNlcnRpZmljYXRlPg0KPC9kczpYNTA5RGF0YT4NCjwvZHM6S2V5SW5mbz4NCjwvS2V5RGVzY3JpcHRvcj4NCjxBdHRyaWJ1dGVTZXJ2aWNlIEJpbmRpbmc9InVybjpvYXNpczpuYW1lczp0YzpTQU1MOjEuMDpiaW5kaW5nczpTT0FQLWJpbmRpbmciIExvY2F0aW9uPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1Ojk0NDMvaWRwL3Byb2ZpbGUvU0FNTDEvU09BUC9BdHRyaWJ1dGVRdWVyeSIvPg0KPEF0dHJpYnV0ZVNlcnZpY2UgQmluZGluZz0idXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOmJpbmRpbmdzOlNPQVAiIExvY2F0aW9uPSJodHRwczovL2lkcC5taWxsZXJzdmlsbGUuZWR1Ojk0NDMvaWRwL3Byb2ZpbGUvU0FNTDIvU09BUC9BdHRyaWJ1dGVRdWVyeSIvPg0KPE5hbWVJREZvcm1hdD51cm46bWFjZTpzaGliYm9sZXRoOjEuMDpuYW1lSWRlbnRpZmllcjwvTmFtZUlERm9ybWF0Pg0KPE5hbWVJREZvcm1hdD4NCnVybjpvYXNpczpuYW1lczp0YzpTQU1MOjIuMDpuYW1laWQtZm9ybWF0OnRyYW5zaWVudA0KPC9OYW1lSURGb3JtYXQ+DQo8TmFtZUlERm9ybWF0Pg0KdXJuOm9hc2lzOm5hbWVzOnRjOlNBTUw6Mi4wOm5hbWVpZC1mb3JtYXQ6cGVyc2lzdGVudA0KPC9OYW1lSURGb3JtYXQ+DQo8L0F0dHJpYnV0ZUF1dGhvcml0eURlc2NyaXB0b3I+DQo8L0VudGl0eURlc2NyaXB0b3I+",
    "entityid": "https://idp.acme.com/idp/shibboleth",
    "organization": "https://ra.org/organization/567ae838-1057-42a8-97be-ba5cb2ea5ae8"
    "parent_entity": "https://ra.org/federation_entity/7d0c11d2-dfbb-40f3-8534-b2aceab6fc9e"
}
```

## Schema definitions

1. *name* - Display name for this IDP
2. *entity_asserted_metadata* - Base-64 encoded XML provided by 
    the organization
3. *federation_asserted_metadata* - Base-64 encoded XML provided by
    the federation after applying filters
4. *entityid* - entityID of the IDP
5. *organization* - Link to organization that controls the IDP
6. *parent_entity* - Link to the entity container that references this IDP.

