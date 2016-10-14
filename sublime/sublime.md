# Sublime 配置及插件

> MacOS  
> sublime text 3

## 安装package control

Ctrl+`打开控制台

```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```

## 常用插件
```
Add Folder To Project //保存sublime关闭时的项目目录
Alignment             //代码对齐
AutoFileName          //提示本地文件路径或在文件中存在的单词
BracketHighlighter    //闭合结构高亮
DocBlockr             //注释语法
HTML-CSS-JS Prettify  //语法格式化
Material Theme        //Material 主题
SublimeCodeIntel      //语法提示
FileHeader            //在文件头部添加文件说明 
```

## sublime settings

```
{
	"always_prompt_for_file_reload": false,
	"always_show_minimap_viewport": true,
	"animation_enabled": true,
	"atomic_save": false,
	"auto_close_tags": true,
	"auto_complete": true,
	"auto_complete_commit_on_tab": false,
	"auto_complete_cycle": false,
	"auto_complete_delay": 50,
	"auto_complete_selector": "meta.tag - punctuation.definition.tag.begin, source - comment - string.quoted.double.block - string.quoted.single.block - string.unquoted.heredoc",
	"auto_complete_size_limit": 4194304,
	"auto_complete_triggers":
	[
		{
			"characters": "<",
			"selector": "text.html"
		}
	],
	"auto_complete_with_fields": false,
	"auto_find_in_selection": false,
	"auto_indent": true,
	"auto_match_enabled": true,
	"binary_file_patterns":
	[
		"*.jpg",
		"*.jpeg",
		"*.png",
		"*.gif",
		"*.ttf",
		"*.tga",
		"*.dds",
		"*.ico",
		"*.eot",
		"*.pdf",
		"*.swf",
		"*.jar",
		"*.zip"
	],
	"bold_folder_labels": true,
	"caret_extra_bottom": 3,
	"caret_extra_top": 3,
	"caret_extra_width": 2,
	"caret_style": "smooth",
	"close_windows_when_empty": false,
	"color_scheme": "Packages/Material Theme/schemes/OLD/Material-Theme.tmTheme",
	"copy_with_empty_selection": true,
	"create_window_at_startup": true,
	"default_encoding": "UTF-8",
	"default_line_ending": "system",
	"detect_indentation": true,
	"dictionary": "Packages/Language - English/en_US.dic",
	"drag_text": true,
	"draw_centered": false,
	"draw_indent_guides": true,
	"draw_minimap_border": false,
	"draw_white_space": "selection",
	"enable_hexadecimal_encoding": true,
	"enable_tab_scrolling": true,
	"ensure_newline_at_eof_on_save": false,
	"fade_fold_buttons": true,
	"fallback_encoding": "Western (Windows 1252)",
	"file_exclude_patterns":
	[
		"*.pyc",
		"*.pyo",
		"*.exe",
		"*.dll",
		"*.obj",
		"*.o",
		"*.a",
		"*.lib",
		"*.so",
		"*.dylib",
		"*.ncb",
		"*.sdf",
		"*.suo",
		"*.pdb",
		"*.idb",
		".DS_Store",
		"*.class",
		"*.psd",
		"*.db",
		"*.sublime-workspace"
	],
	"find_selected_text": true,
	"fold_buttons": true,
	"folder_exclude_patterns":
	[
		".svn",
		".git",
		".hg",
		"CVS"
	],
	"font_face": "Monaco",
	"font_options":
	[
		"directwrite"
	],
	"font_size": 12,
	"gpu_window_buffer": "auto",
	"gutter": true,
	"highlight_line": true,
	"highlight_modified_tabs": false,
	"hot_exit": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_guide_options":
	[
		"draw_normal",
		"draw_active"
	],
	"indent_subsequent_lines": true,
	"indent_to_bracket": false,
	"index_exclude_patterns":
	[
		"*.log"
	],
	"index_files": true,
	"index_workers": 0,
	"line_numbers": true,
	"line_padding_bottom": 3,
	"line_padding_top": 3,
	"margin": 4,
	"match_brackets": true,
	"match_brackets_angle": false,
	"match_brackets_braces": true,
	"match_brackets_content": true,
	"match_brackets_square": true,
	"match_selection": true,
	"match_tags": true,
	"material_theme_accent_sky": true,
	"material_theme_bold_tab": true,
	"material_theme_compact_panel": true,
	"material_theme_panel_separator": true,
	"material_theme_small_statusbar": true,
	"material_theme_tabs_separator": true,
	"material_theme_tree_headings": true,
	"move_to_limit_on_up_down": false,
	"open_files_in_new_window": true,
	"overlay_scroll_bars": "enabled",
	"preview_on_click": true,
	"remember_full_screen": false,
	"rulers":
	[
	],
	"save_on_focus_lost": false,
	"scroll_past_end": true,
	"scroll_speed": 1.0,
	"shift_tab_unindent": false,
	"show_definitions": true,
	"show_encoding": false,
	"show_errors_inline": true,
	"show_full_path": true,
	"show_line_endings": false,
	"show_panel_on_build": true,
	"show_tab_close_buttons": true,
	"smart_indent": true,
	"spell_check": false,
	"spelling_selector": "markup.raw, source string.quoted - punctuation - meta.preprocessor.c.include, source comment - source comment.block.preprocessor, -(source, constant, keyword, storage, support, variable, markup.underline.link, meta.tag)",
	"tab_completion": true,
	"tab_size": 4,
	"theme": "Material-Theme.sublime-theme",
	"translate_tabs_to_spaces": false,
	"tree_animation_enabled": true,
	"trim_automatic_white_space": true,
	"trim_trailing_white_space_on_save": false,
	"use_simple_full_screen": false,
	"use_tab_stops": true,
	"word_separators": "./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}`~?",
	"word_wrap": "auto",
	"wrap_width": 0
}

```

