# Function: <code>bpf_arch_text_poke</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a2790)
Location: arch/x86/net/bpf_jit_comp.c:329
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff810a2790-ffffffff810a27ff: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109e0b0)
Location: arch/x86/net/bpf_jit_comp.c:364
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8109e0b0-ffffffff8109e11f: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109eec0)
Location: arch/x86/net/bpf_jit_comp.c:376
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8109eec0-ffffffff8109ef2f: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0080)
Location: arch/x86/net/bpf_jit_comp.c:372
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff810b0080-ffffffff810b00ef: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c5e10)
Location: arch/x86/net/bpf_jit_comp.c:391
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff810c5e10-ffffffff810c5e83: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e2bd0)
Location: arch/x86/net/bpf_jit_comp.c:399
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
```
**Symbols:**

```
ffffffff810e2bd0-ffffffff810e2c43: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ee2a0)
Location: arch/x86/net/bpf_jit_comp.c:399
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
```
**Symbols:**

```
ffffffff810ee2a0-ffffffff810ee313: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f7d60)
Location: arch/x86/net/bpf_jit_comp.c:521
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
```
**Symbols:**

```
ffffffff810f7d60-ffffffff810f7dd3: bpf_arch_text_poke (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
