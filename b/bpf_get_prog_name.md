# Function: <code>bpf_get_prog_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118ce80)
Location: kernel/bpf/core.c:310
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff8118ce80-ffffffff8118ceb9: bpf_get_prog_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119a970)
Location: kernel/bpf/core.c:306
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff8119a970-ffffffff8119a9e3: bpf_get_prog_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b0540)
Location: kernel/bpf/core.c:387
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811b0540-ffffffff811b05b6: bpf_get_prog_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811beb60)
Location: kernel/bpf/core.c:498
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811beb60-ffffffff811bec35: bpf_get_prog_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d0f80)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff811d0f80-ffffffff811d1038: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dd510)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff811dd510-ffffffff811dd5c8: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e0a8)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffff80001025e0a8-ffff80001025e190: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491784)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
c0491784-c0491854: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000302d00)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
c000000000302d00-c000000000302e4c: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c556)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffe00019c556-ffffffe00019c676: bpf_get_prog_name (STB_GLOBAL)
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
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5b30)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff811d5b30-ffffffff811d5be8: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c88f0)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff811c88f0-ffffffff811c89a8: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3900)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff811d3900-ffffffff811d39b8: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog *prog, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e1bf0)
Location: kernel/bpf/core.c:540
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff811e1bf0-ffffffff811e1ca8: bpf_get_prog_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
