# Personal Weekly Health Review

A personal, non-commercial tool for reviewing my own Oura sleep,
readiness and activity data through weekly automated reports.
This application is for the owner's use only and is not open
for registration by other users.

## Privacy Policy

This application accesses the owner's Oura data only after
authorization through Oura OAuth.

Data is processed on the owner's computer or in a private
GitHub Actions workflow. Aggregated health statistics are sent
to the OpenAI API to generate a weekly report. If email delivery
is enabled, the report is also processed by the configured
email provider.

Health data, reports and credentials are not published in this
public repository. Reports are stored locally or as private
GitHub Actions artifacts. OAuth tokens are stored encrypted,
with the encryption key stored separately.

Data is not sold or used for advertising. GitHub, OpenAI and
any configured email provider process data under their
respective policies; this application does not promise zero
retention by those providers.

The owner can stop scheduled workflows, revoke Oura access,
and delete local reports and GitHub artifacts. Existing copies
and provider records may remain subject to retention policies.

For questions, contact the repository owner through the
GitHub profile linked to this repository. Do not post health
data or credentials in public issues.

## Terms of Service

This tool is intended solely for the owner's personal,
non-commercial wellness review.

Reports may contain errors and are for informational purposes
only. They are not medical advice, diagnosis or treatment and
must not be used for emergencies or medical decisions.

The tool is provided "as is" and "as available", without
warranties of any kind, including on behalf of third-party
providers, to the extent permitted by applicable law.
This includes implied warranties of merchantability, fitness
for a particular purpose and non-infringement.

To the extent permitted by applicable law, third-party service
providers are not liable for consequential, special, punitive
or indirect damages arising from use of this tool.

The owner is responsible for protecting credentials, managing
access and API costs, and complying with the applicable terms
of Oura, GitHub, OpenAI and any email provider.

This project is independent and is not endorsed by Oura,
GitHub or OpenAI.
