valgrind --leak-check=full --show-leak-kinds=all --track-origins=yes --suppressions=supp_readline.supp -s


CREATE FILE : supp_readline.supp


{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_make_bare_keymap
   fun:rl_generic_bind
   fun:rl_parse_and_bind
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_make_bare_keymap
   fun:rl_generic_bind
   fun:rl_bind_keyseq_if_unbound_in_map
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_make_bare_keymap
   fun:rl_generic_bind
   fun:rl_bind_keyseq_if_unbound_in_map
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_make_bare_keymap
   fun:rl_generic_bind
   fun:rl_bind_keyseq_if_unbound_in_map
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:calloc
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_find_type_entry
   fun:tgetstr_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:realloc
   fun:_nc_doalloc
   fun:_nc_read_termtype
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_read_entry2
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_add_funmap_entry
   fun:rl_initialize_funmap
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:_nc_read_termtype
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_read_entry2
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:realloc
   fun:xrealloc
   fun:rl_add_funmap_entry
   fun:rl_initialize_funmap
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_redisplay
   fun:readline_internal_setup
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xrealloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_redisplay
   fun:readline_internal_setup
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:calloc
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:calloc
   fun:_nc_read_termtype
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_read_entry2
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:calloc
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_trim_sgr0
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:_nc_first_db
   fun:_nc_read_entry2
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:_nc_tparm_analyze
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_trim_sgr0
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:strdup
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_trim_sgr0
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_expand_prompt
   fun:rl_set_prompt
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:calloc
   fun:_nc_first_db
   fun:_nc_read_entry2
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_set_prompt
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:_nc_home_terminfo
   fun:_nc_first_db
   fun:_nc_read_entry2
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:tsearch
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_trim_sgr0
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_parse_and_bind
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:strdup
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:strdup
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_first_db
   fun:_nc_read_entry2
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_setupterm
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:readline_internal_teardown
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:realloc
   fun:_nc_doalloc
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_trim_sgr0
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:realloc
   fun:xrealloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_expand_prompt
   fun:rl_set_prompt
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:strdup
   fun:_nc_trim_sgr0
   fun:tgetent_sp
   fun:_rl_init_terminal_io
   fun:rl_initialize
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xrealloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_expand_prompt
   fun:rl_set_prompt
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: indirect
   fun:malloc
   fun:xmalloc
   fun:rl_copy_text
   fun:rl_delete_text
   fun:_rl_rubout_char
   fun:_rl_dispatch_subseq
   fun:readline_internal_char
   fun:readline
   fun:main

}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_maybe_save_line
   fun:rl_get_previous_history
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:replace_history_entry
   fun:readline_internal_teardown
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:strdup
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_redisplay
   fun:_rl_internal_char_cleanup
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:tsearch
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_redisplay
   fun:_rl_internal_char_cleanup
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: definite
   fun:malloc
   fun:xmalloc
   fun:rl_add_undo
   fun:rl_insert_text
   fun:rl_bracketed_paste_begin
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:readline_internal_char
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:rl_add_undo
   fun:rl_delete_text
   fun:_rl_rubout_char
   fun:_rl_dispatch_subseq
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: definite
   fun:malloc
   fun:xmalloc
   fun:rl_add_undo
   fun:rl_delete_text
   fun:_rl_rubout_char
   fun:_rl_dispatch_subseq
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:realloc
   fun:xrealloc
   fun:rl_extend_line_buffer
   fun:rl_insert_text
   fun:rl_bracketed_paste_begin
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:_rl_dispatch_subseq
   fun:readline_internal_char
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:realloc
   fun:xrealloc
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_redisplay
   fun:_rl_internal_char_cleanup
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:realloc
   fun:_nc_doalloc
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_redisplay
   fun:_rl_internal_char_cleanup
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   supp_readline
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:calloc
   obj:/usr/lib/x86_64-linux-gnu/libtinfo.so.6.3
   fun:_nc_tiparm
   obj:/usr/lib/x86_64-linux-gnu/libreadline.so.8.1
   fun:rl_redisplay
   fun:_rl_internal_char_cleanup
   fun:readline_internal_char
   fun:readline
   fun:main
}
{
   CLEAR_HISTORY
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:add_history
   fun:main
}
{
   CLEAR_HISTORY
   Memcheck:Leak
   match-leak-kinds: reachable
   fun:malloc
   fun:xmalloc
   fun:alloc_history_entry
   fun:add_history
   fun:main
}
