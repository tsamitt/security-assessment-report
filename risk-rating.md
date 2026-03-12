# Risk Rating

## Rating Scale

- Low - limited impact and easier to manage
- Medium - meaningful risk requiring remediation
- High - serious risk with major security impact

## Findings by Severity

### High Severity

**Broken Access Control**  
If users can reach data or functions outside their role, confidentiality and integrity can be seriously affected.

**Insecure Input Handling**  
Input-related weaknesses can create serious application risk depending on implementation.

### Medium Severity

**Weak Authentication Controls**  
Weak passwords or missing account protections can increase the likelihood of unauthorized access.

**Insecure File Upload Handling**  
File handling issues may become serious depending on storage and processing logic.

**Weak Transport Security**  
Unencrypted or poorly configured traffic can expose sensitive data.

### Medium to Low Severity

**Insufficient Logging and Monitoring**  
This may not directly create an initial compromise, but it makes detection and response much harder.

## Prioritization Strategy

High-severity issues should be addressed first, followed by medium-severity weaknesses that increase likelihood of compromise or reduce defensive visibility.
