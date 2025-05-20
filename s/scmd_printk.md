# Function: <code>scmd_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b7e00)
Location: drivers/scsi/scsi_logging.c:123
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff815b7e00-ffffffff815b7f0c: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81610680)
Location: drivers/scsi/scsi_logging.c:123
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81610680-ffffffff8161078c: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8163ff10)
Location: drivers/scsi/scsi_logging.c:123
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8163ff10-ffffffff8164001c: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81654940)
Location: drivers/scsi/scsi_logging.c:123
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81654940-ffffffff81654a5c: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816bde90)
Location: drivers/scsi/scsi_logging.c:123
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff816bde90-ffffffff816bdfac: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816fa450)
Location: drivers/scsi/scsi_logging.c:123
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff816fa450-ffffffff816fa55a: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171ce90)
Location: drivers/scsi/scsi_logging.c:123
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8171ce90-ffffffff8171cf95: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:122
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81759096-ffffffff817590c0: scmd_printk.cold (STB_LOCAL)
ffffffff81758460-ffffffff81758545: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8177d20e-ffffffff8177d238: scmd_printk.cold (STB_LOCAL)
ffffffff8177cee0-ffffffff8177cfd7: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8184063f-ffffffff81840669: scmd_printk.cold (STB_LOCAL)
ffffffff8183fec0-ffffffff8183ffb2: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81c16c25-ffffffff81c16c4f: scmd_printk.cold (STB_LOCAL)
ffffffff81850520-ffffffff81850612: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81c08a6e-ffffffff81c08a98: scmd_printk.cold (STB_LOCAL)
ffffffff818335b0-ffffffff818336a2: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:81
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81d0cb53-ffffffff81d0cb7d: scmd_printk.cold (STB_LOCAL)
ffffffff818bf600-ffffffff818bf6ee: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:83
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81ed5a37-ffffffff81ed5a60: scmd_printk.cold (STB_LOCAL)
ffffffff81a0bab0-ffffffff81a0bbce: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8b310)
Location: drivers/scsi/scsi_logging.c:83
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81b8b310-ffffffff81b8b454: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdf310)
Location: drivers/scsi/scsi_logging.c:83
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81bdf310-ffffffff81bdf454: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c34230)
Location: drivers/scsi/scsi_logging.c:83
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_cmd_runtime_exceeced
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81c34230-ffffffff81c343a2: scmd_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffff800010983190)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffff800010983190-ffff8000109832b0: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a55b40)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
c0a55b40-c0a55c30: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3fa90)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
c000000000a3fa90-c000000000a3fb9c: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e88b6)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffe0005e88b6-ffffffe0005e8974: scmd_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff817318fe-ffffffff81731928: scmd_printk.cold (STB_LOCAL)
ffffffff817315d0-ffffffff817316c7: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8170ad1e-ffffffff8170ad48: scmd_printk.cold (STB_LOCAL)
ffffffff8170a9f0-ffffffff8170aae7: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff817706ce-ffffffff817706f8: scmd_printk.cold (STB_LOCAL)
ffffffff817703a0-ffffffff81770497: scmd_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void scmd_printk(const char *level, const struct scsi_cmnd *scmd, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:80
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_tur
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff8178be6e-ffffffff8178be98: scmd_printk.cold (STB_LOCAL)
ffffffff8178bb40-ffffffff8178bc37: scmd_printk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
