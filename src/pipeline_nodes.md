# Pipeline Nodes

This project was implemented in a notebook-first style. The production-oriented next step would be to split the following nodes into Python modules:

- `node_parse_all`
- `node_build_vector_db`
- `node_tool_search`
- `node_generate_page`
- `node_generate_script_ctx`
- `node_retouch_script`
- `node_gen_subtitle`
- `node_highlight_keywords`
- `node_tts`
- `node_make_video`
- `node_burn_subtitle`
- `node_generate_quiz`
- `node_concat_videos`

The notebook in `notebooks/ai_instructor_agent.ipynb` contains the complete implementation and Colab execution flow.
