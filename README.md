# AI Agents telemetry Benchmark

Predicting human intervention in autonomous AI-agent execution

Project currently in development.

### Current progress

* Initial data cleaning completed
* Cleaned `timestamp` formats and standardized `company_sector`
* Removed `session_id` as it is only an identifier
* Investigated `prompt_summary`, `error_log_snippet`, and other suspicious features
* Identified `intervention_reason`, `task_status`, `human_satisfaction_score`, and `post_task_bug_detected` as potential data leakage
* `error_log_snippet` and `reasoning_tokens` are still under investigation
* Further feature removal/selection will be done after feature-target relationship analysis
