{\rtf1\ansi\ansicpg936\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww12920\viewh7080\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \{\
  "which_key": \{\
    "enabled": true\
  \},\
  "autosave": "on_window_change",\
  "autosave_delay_ms": 1000,\
  "base_keymap": "Cursor",\
  "theme": "One Dark",\
  "icon_theme": "Material Icon Theme",\
  "ui_font_family": "Source Code Pro",\
  "ui_font_size": 16,\
  "buffer_font_family": "Source Code Pro",\
  "buffer_font_size": 16,\
  "tab_size": 2,\
  "hard_tabs": false,\
  "format_on_save": "on",\
  "remove_trailing_whitespace_on_save": true,\
  "ensure_final_newline_on_save": true,\
  "show_line_numbers": true,\
  "relative_line_numbers": false,\
  "indent_guides": \{\
    "enabled": true,\
    "line_width": 1,\
    "active_line_width": 2,\
    "coloring": "fixed"\
  \},\
  "project_panel": \{\
    "button": true,\
    "default_width": 240,\
    "dock": "left",\
    "auto_reveal_entries": true,\
    "folder_icons": true,\
    "git_status": true\
  \},\
  "tabs": \{\
    "git_status": true,\
    "close_position": "right",\
    "file_icons": true,\
    "show_diagnostics": "errors"\
  \},\
  "minimap": \{\
    "show": "always",\
    "git_diff": true\
  \},\
  "title_bar": \{\
    "show_branch_icon": true,\
    "show_menus": true\
  \},\
  "git": \{\
    "inline_blame": \{\
      "enabled": true,\
      "show_commit_summary": true,\
      "delay_ms": 500\
    \},\
    "gutter_deletions": true,\
    "gutter_insertions": true,\
    "show_inline_comparisons": true,\
    "auto_fetch": true\
  \},\
  "diagnostics": \{\
    "include_warnings": true,\
    "show_inline": true,\
    "show_summary": true,\
    "inline": \{\
      "enabled": true,\
      "update_delay_ms": 200\
    \}\
  \},\
  "preview_tabs": \{\
    "enabled": true,\
    "enable_preview_from_file_finder": true,\
    "enable_preview_from_code_navigation": true\
  \},\
  "scrollbar": \{\
    "show": "always",\
    "git_diff": true,\
    "diagnostics": true\
  \},\
  "toolbar": \{\
    "breadcrumbs": true,\
    "quick_actions": true\
  \},\
  "auto_update": true,\
  "load_direnv": "shell_hook",\
  "features": \{\
    "edit_prediction_provider": "zed",\
    "copilot": false\
  \},\
  "telemetry": \{\
    "diagnostics": false,\
    "metrics": false\
  \},\
  "file_scan_exclusions": [\
    "**/.env*",\
    "**/*.pem",\
    "**/*.key",\
    "**/*_rsa",\
    "**/secrets.json",\
    "**/node_modules",\
    "**/.git",\
    "**/.venv",\
    "**/venv",\
    "**/__pycache__",\
    "**/.pytest_cache",\
    "**/.mypy_cache",\
    "**/.DS_Store",\
    "**/target",\
    "**/dist",\
    "**/build",\
    "**/.idea",\
    "**/.vscode",\
    "**/*.lock",\
    "**/Cargo.lock",\
    "**/package-lock.json",\
    "**/yarn.lock",\
    "**/pnpm-lock.yaml"\
  ],\
  "edit_predictions": \{\
    "mode": "aggressive",\
    "copilot": \{\
      "proxy": null,\
      "disable_completion_settings": false\
    \},\
    "enabled_in_assistant": false\
  \},\
  "terminal": \{\
    "font_family": "Source Code Pro",\
    "font_size": 14,\
    "line_height": "comfortable",\
    "shell": "system",\
    "working_directory": "current_project_directory",\
    "detect_venv": \{\
      "on": \{\
        "directories": [".venv", "venv", ".env", "env", "envs"],\
        "activate_script": "auto"\
      \}\
    \},\
    "cursor_style": "bar",\
    "option_as_meta": true,\
    "copy_on_select": true\
  \},\
  "ssh_connections": [\
    \{\
      "host": "zed-openclaw",\
      "args": [],\
      "projects": [\
        \{\
          "paths": ["/config"]\
        \}\
      ]\
    \}\
  ],\
  "git_hosting_providers": [\
    \{\
      "provider": "gitlab",\
      "name": "Self Host Git",\
      "base_url": "http://192.168.1.110/"\
    \}\
  ],\
  "lsp": \{\
    "clangd": \{\
      "binary": \{\
        "path": "D:/clangd/bin/clangd.exe",\
        "arguments": [\
          "--compile-commands-dir=.edkCode",\
          "--header-insertion=never",\
          "--clang-tidy"\
        ]\
      \}\
    \},\
    "rust-analyzer": \{\
      "initialization_options": \{\
        "checkOnSave": \{\
          "command": "clippy"\
        \},\
        "cargo": \{\
          "features": "all"\
        \},\
        "procMacro": \{\
          "enable": true\
        \}\
      \}\
    \}\
  \},\
  "languages": \{\
    "Python": \{\
      "format_on_save": \{\
        "external": \{\
          "command": "black",\
          "arguments": ["-"]\
        \}\
      \},\
      "tab_size": 4\
    \},\
    "Rust": \{\
      "format_on_save": "on",\
      "tab_size": 4\
    \},\
    "JavaScript": \{\
      "tab_size": 2\
    \},\
    "TypeScript": \{\
      "tab_size": 2\
    \}\
  \},\
  "agent": \{\
    "default_profile": "ultra_mode",\
    "show_turn_stats": true,\
    "stream_edits": true,\
    "enable_experimental_live_diffs": true,\
    "default_model": \{\
      "provider": "kimi",\
      "model": "kimi-k2.5",\
      "enable_thinking": true\
    \},\
    "profiles": \{\
      "ultra_mode": \{\
        "name": "Ultra Mode",\
        "tools": \{\
          "code_reader": true,\
          "code_writer": true,\
          "terminal": true,\
          "browser": false,\
          "diagnostics": true,\
          "fetch": true,\
          "now": true\
        \},\
        "enable_offline_mode": false\
      \},\
      "background_mode": \{\
        "name": "Background Agent",\
        "tools": \{\
          "code_reader": true,\
          "code_writer": false,\
          "terminal": false,\
          "diagnostics": true\
        \},\
        "auto_run": true\
      \}\
    \},\
    "llm": \{\
      "default_provider": "moonshot",\
      "providers": \{\
        "moonshot": \{\
          "api_key": "sk-...",\
          "api_endpoint": "https://api.moonshot.cn/v1",\
          "default_model": "kimi-k2.5",\
          "available_models": [\
            "kimi-k2.5",\
            "moonshot-v1-8k",\
            "moonshot-v1-32k",\
            "moonshot-v1-128k",\
            "moonshot-v1-256k"\
          ],\
          "request_timeout_ms": 120000\
        \},\
        "local_kimi_distill": \{\
          "api_key": "local",\
          "api_endpoint": "http://localhost:11434/v1",\
          "default_model": "kimi-distill-32k",\
          "available_models": [\
            "kimi-distill-8k",\
            "kimi-distill-32k",\
            "kimi-distill-code"\
          ],\
          "request_timeout_ms": 30000\
        \}\
      \}\
    \},\
    "model_routing": \{\
      "enabled": true,\
      "rules": [\
        \{\
          "task_pattern": "simple_completion|line_edit|small_change",\
          "provider": "local_kimi_distill",\
          "model": "kimi-distill-8k",\
          "priority": 1\
        \},\
        \{\
          "task_pattern": "code_review|bug_find|explain",\
          "provider": "local_kimi_distill",\
          "model": "kimi-distill-32k",\
          "priority": 2\
        \},\
        \{\
          "task_pattern": "architecture|large_refactor|complex_debug",\
          "provider": "moonshot",\
          "model": "kimi-k2.5",\
          "priority": 0\
        \}\
      ]\
    \}\
  \},\
  "language_models": \{\
    "openai_compatible": \{\
      "kimi": \{\
        "api_url": "https://api.moonshot.cn/v1",\
        "available_models": [\
          \{\
            "name": "kimi-k2.5",\
            "display_name": "Kimi K2.5 Ultra",\
            "max_tokens": 256000,\
            "max_output_tokens": 16000,\
            "max_completion_tokens": 256000,\
            "capabilities": \{\
              "tools": true,\
              "images": true,\
              "parallel_tool_calls": true,\
              "prompt_cache_key": true,\
              "chat_completions": true\
            \}\
          \},\
          \{\
            "name": "moonshot-v1-128k",\
            "display_name": "Kimi 128k",\
            "max_tokens": 128000,\
            "max_output_tokens": 8000,\
            "max_completion_tokens": 128000,\
            "capabilities": \{\
              "tools": true,\
              "images": false,\
              "parallel_tool_calls": true,\
              "prompt_cache_key": true,\
              "chat_completions": true\
            \}\
          \},\
          \{\
            "name": "kimi-distill-32k",\
            "display_name": "Kimi Distill 32k (Local)",\
            "max_tokens": 32000,\
            "max_output_tokens": 4096,\
            "max_completion_tokens": 32000,\
            "capabilities": \{\
              "tools": true,\
              "images": false,\
              "parallel_tool_calls": false,\
              "prompt_cache_key": false,\
              "chat_completions": true\
            \}\
          \}\
        ]\
      \},\
      "local_ollama": \{\
        "api_url": "http://localhost:11434/v1",\
        "available_models": [\
          \{\
            "name": "kimi-distill-code",\
            "display_name": "Kimi Code Predict (Local)",\
            "max_tokens": 8192,\
            "max_output_tokens": 1024,\
            "max_completion_tokens": 8192,\
            "capabilities": \{\
              "tools": false,\
              "images": false,\
              "parallel_tool_calls": false,\
              "prompt_cache_key": false,\
              "chat_completions": true\
            \}\
          \}\
        ]\
      \}\
    \}\
  \},\
  "agent_servers": \{\
    "kimi": \{\
      "type": "registry"\
    \},\
    "local_mcp": \{\
      "type": "stdio",\
      "command": "npx",\
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/your/project"]\
    \}\
  \},\
  "experimental": \{\
    "agent_cluster": \{\
      "enabled": true,\
      "mode": "background_first",\
      "max_concurrent_agents": 3,\
      "thread_pool_size": 4,\
      "kimi-code-cli": \{\
        "workspace_permissions": ["read", "write", "execute"],\
        "command_timeout": 60000,\
        "auto_fix_errors": false\
      \},\
      "roles": \{\
        "primary_coder": \{\
          "model": "kimi-k2.5",\
          "provider": "moonshot",\
          "workspace_permissions": ["read", "write", "execute"],\
          "auto_trigger": ["on_explicit_request", "on_complex_task"],\
          "system_prompt": "You are the primary coding assistant. Focus on generating high-quality, production-ready code."\
        \},\
        "fast_completer": \{\
          "model": "kimi-distill-8k",\
          "provider": "local_kimi_distill",\
          "workspace_permissions": ["read"],\
          "auto_trigger": ["on_tab_request", "on_line_completion"],\
          "system_prompt": "Provide fast, accurate code completions. Respond in 1-2 lines maximum."\
        \},\
        "code_reviewer": \{\
          "model": "kimi-distill-32k",\
          "provider": "local_kimi_distill",\
          "workspace_permissions": ["read"],\
          "auto_trigger": ["on_save", "on_git_stage"],\
          "system_prompt": "Review code for bugs, security issues, and performance problems. Be concise."\
        \},\
        "test_generator": \{\
          "model": "kimi-distill-32k",\
          "provider": "local_kimi_distill",\
          "workspace_permissions": ["read", "write"],\
          "auto_trigger": ["on_file_open", "on_request"],\
          "system_prompt": "Generate unit tests for the current code. Cover edge cases."\
        \},\
        "context_indexer": \{\
          "model": "kimi-embedding",\
          "provider": "local_kimi_distill",\
          "workspace_permissions": ["read"],\
          "auto_trigger": ["on_project_open", "on_idle"],\
          "system_prompt": "Index and summarize code context for retrieval."\
        \}\
      \},\
      "background_watchers": \{\
        "syntax_validator": \{\
          "enabled": true,\
          "trigger_events": ["save", "edit"],\
          "model": "kimi-distill-8k",\
          "check_interval_ms": 500,\
          "max_file_size_kb": 500\
        \},\
        "bugbot": \{\
          "enabled": true,\
          "trigger_events": ["save", "agent_edit"],\
          "model": "kimi-distill-32k",\
          "focus_areas": ["null_safety", "memory_leaks", "race_conditions", "sql_injection"],\
          "action": "inline_warning",\
          "severity_threshold": "warning"\
        \},\
        "security_scanner": \{\
          "enabled": true,\
          "trigger_events": ["save", "git_stage"],\
          "model": "kimi-distill-32k",\
          "patterns": ["secret_key", "password", "api_key", "token"],\
          "action": "block_commit"\
        \}\
      \}\
    \},\
    "context_engine": \{\
      "enabled": true,\
      "type": "hierarchical_rag",\
      "max_context_tokens": 2000000,\
      "indexing": \{\
        "provider": "kimi-embedding",\
        "granularity": ["file", "class", "function", "chunk"],\
        "chunk_size": 512,\
        "chunk_overlap": 128,\
        "auto_index_on_open": true,\
        "index_git_tracked_only": true,\
        "excluded_patterns": ["*.min.js", "*.lock", "dist/*", "build/*"]\
      \},\
      "retrieval": \{\
        "top_k": 15,\
        "reranker": "kimi-distill-reranker",\
        "dynamic_context_window": true,\
        "auto_expand_context": true,\
        "min_relevance_score": 0.7\
      \},\
      "caching": \{\
        "enabled": true,\
        "max_cache_size_mb": 2048,\
        "ttl_minutes": 60\
      \}\
    \},\
    "predictive_edits": \{\
      "enabled": true,\
      "mode": "local_lora",\
      "model": \{\
        "type": "local_lora",\
        "base_model": "kimi-distill-1.5b-code",\
        "quantization": "int4",\
        "device": "auto",\
        "context_lines": 128,\
        "max_tokens": 256,\
        "temperature": 0.2\
      \},\
      "trigger": \{\
        "min_typing_pause_ms": 50,\
        "max_predictions": 3,\
        "debounce_ms": 30\
      \},\
      "ui": \{\
        "ghost_text": true,\
        "accept_keybinding": "tab",\
        "dismiss_keybinding": "escape",\
        "next_suggestion": "alt_right"\
      \}\
    \},\
    "browser_integration": \{\
      "enabled": false,\
      "type": "playwright",\
      "auto_launch_on_preview": true,\
      "viewport": \{\
        "width": 1280,\
        "height": 720\
      \},\
      "allowed_hosts": ["localhost", "127.0.0.1"]\
    \},\
    "inline_assist": \{\
      "enabled": true,\
      "model": "kimi-distill-32k",\
      "trigger_character": "@",\
      "commands": \{\
        "explain": "Explain this code",\
        "refactor": "Refactor this",\
        "test": "Generate tests",\
        "doc": "Add documentation"\
      \}\
    \}\
  \},\
  "notification": \{\
    "enabled": true,\
    "show_agent_updates": true,\
    "show_diagnostics_summary": true,\
    "background_agent_alerts": true\
  \},\
  "outline_panel": \{\
    "enabled": true,\
    "default_width": 280,\
    "dock": "right"\
  \},\
  "collaboration": \{\
    "enabled": false\
  \},\
  "vim_mode": false,\
  "soft_wrap": "none",\
  "preferred_line_length": 100,\
  "ensure_final_newline": true,\
  "remove_trailing_whitespace": true,\
  "extend_comment_on_newline": true,\
  "show_wrap_guides": true,\
  "wrap_guides": [80, 100, 120]\
\}}