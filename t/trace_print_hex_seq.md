# Function: <code>trace_print_hex_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81153a80)
Location: kernel/trace/trace_output.c:166
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
```
**Symbols:**

```
ffffffff81153a80-ffffffff81153b1e: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8115cbe0)
Location: kernel/trace/trace_output.c:166
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
```
**Symbols:**

```
ffffffff8115cbe0-ffffffff8115cc7e: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811674b0)
Location: kernel/trace/trace_output.c:166
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
```
**Symbols:**

```
ffffffff811674b0-ffffffff8116754e: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8116a7f0)
Location: kernel/trace/trace_output.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - kernel/bpf/core.c:trace_raw_output_bpf_map_next_key
  - kernel/bpf/core.c:trace_raw_output_bpf_map_next_key
  - kernel/bpf/core.c:trace_raw_output_bpf_map_delete_elem
  - kernel/bpf/core.c:trace_raw_output_bpf_map_keyval
  - kernel/bpf/core.c:trace_raw_output_bpf_map_keyval
  - kernel/bpf/core.c:trace_raw_output_bpf_obj_prog
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_load
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_event
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
```
**Symbols:**

```
ffffffff8116a7f0-ffffffff8116a8a0: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81177920)
Location: kernel/trace/trace_output.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:trace_raw_output_bpf_map_next_key
  - kernel/bpf/core.c:trace_raw_output_bpf_map_next_key
  - kernel/bpf/core.c:trace_raw_output_bpf_map_delete_elem
  - kernel/bpf/core.c:trace_raw_output_bpf_map_keyval
  - kernel/bpf/core.c:trace_raw_output_bpf_map_keyval
  - kernel/bpf/core.c:trace_raw_output_bpf_obj_prog
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_load
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_event
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
```
**Symbols:**

```
ffffffff81177920-ffffffff811779d0: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81186b40)
Location: kernel/trace/trace_output.c:216
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
```
**Symbols:**

```
ffffffff81186b40-ffffffff81186bd0: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811944b0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
```
**Symbols:**

```
ffffffff811944b0-ffffffff81194540: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a21d0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811a21d0-ffffffff811a2263: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811adbb0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811adbb0-ffffffff811adc4a: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c5c70)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811c5c70-ffffffff811c5d0c: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c32a0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811c32a0-ffffffff811c333c: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c4300)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811c4300-ffffffff811c4398: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811ef6c0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811ef6c0-ffffffff811ef758: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81227bc0)
Location: kernel/trace/trace_output.c:218
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff81227bc0-ffffffff81227c66: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81273150)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_bulk
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff81273150-ffffffff812731f6: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8128a4f0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_bulk
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff8128a4f0-ffffffff8128a5b7: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812a58a0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_bulk
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff812a58a0-ffffffff812a5967: trace_print_hex_seq (STB_GLOBAL)
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
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffff80001022aec8)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffff80001022aec8-ffff80001022af78: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0468528)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
c0468528-c04685b4: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0000000002b2bd0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
c0000000002b2bd0-c0000000002b2cc4: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffe0001850b2)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffe0001850b2-ffffffe000185142: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a61d0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811a61d0-ffffffff811a626a: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81199150)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff81199150-ffffffff811991ea: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a3fa0)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811a3fa0-ffffffff811a403a: trace_print_hex_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *trace_print_hex_seq(struct trace_seq *p, const unsigned char *buf, int buf_len, bool concatenate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811b1d30)
Location: kernel/trace/trace_output.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ras/ras.c:trace_raw_output_non_standard_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
```
**Symbols:**

```
ffffffff811b1d30-ffffffff811b1dca: trace_print_hex_seq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool concatenate</code>
</li>
</ul>
</details>
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
