# vscan-csp-analyzer
Analyzes Content Security Policy (CSP) headers and reports potential bypasses or weaknesses, such as overly permissive wildcards or 'unsafe-inline' usage. A fetched page with no CSP header is reported as a finding, "No CSP header found." If the URL cannot be fetched at all, the tool prints a failure line and exits 1 with no analysis. - Focused on Lightweight web application vulnerability scanning focused on identifying common misconfigurations and publicly known vulnerabilities

## Install
`git clone https://github.com/ShadowStrikeHQ/vscan-csp-analyzer`

## Usage
`./vscan-csp-analyzer [params]`

## Parameters
- `-h`: Show help message and exit
- `-v`: Enable verbose output for debugging.
- `-o`: Output file to save the results.

## License
Copyright (c) ShadowStrikeHQ
