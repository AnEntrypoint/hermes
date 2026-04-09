## [Unreleased]

### Added
- `opencode-acp` provider: subprocess client using `opencode run PROMPT --format json` (agent/opencode_client.py)
- `kilocode-acp` provider: subprocess client using `kilo run PROMPT --format json` (agent/kilocode_client.py)
- `gemini-acp` provider: subprocess client using `gemini --prompt PROMPT --output-format stream-json` (agent/gemini_client.py)
- All three registered in PROVIDER_REGISTRY (auth_type=acp), resolve_acp_provider_credentials, run_agent.py dispatch, and hermes model setup wizard
- Aliases: oc-acp, kilo-acp, kc-acp, gem-acp
