# Function: <code>stack_map_get_build_id_offset</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811d0c40)
Location: kernel/bpf/stackmap.c:283
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811d0c40-ffffffff811d1099: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811e0720)
Location: kernel/bpf/stackmap.c:287
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811e0720-ffffffff811e0bc5: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f6310)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811f6310-ffffffff811f67ce: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812032d0)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff812032d0-ffffffff8120378c: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8122b3f0)
Location: kernel/bpf/stackmap.c:284
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff8122b3f0-ffffffff8122b5e1: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81233460)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81233460-ffffffff8123369d: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81237220)
Location: kernel/bpf/stackmap.c:147
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81237220-ffffffff81237455: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81271800)
Location: kernel/bpf/stackmap.c:148
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81271800-ffffffff81271a2c: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812c0920)
Location: kernel/bpf/stackmap.c:127
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff812c0920-ffffffff812c0ba7: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff813241c0)
Location: kernel/bpf/stackmap.c:127
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff813241c0-ffffffff81324437: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81354400)
Location: kernel/bpf/stackmap.c:124
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81354400-ffffffff8135469a: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8137cd70)
Location: kernel/bpf/stackmap.c:124
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff8137cd70-ffffffff8137d00a: stack_map_get_build_id_offset (STB_LOCAL)
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
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffff80001028ba50)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffff80001028ba50-ffff80001028bf04: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c04bb100)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
c04bb100-c04bb5b4: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c000000000337a10)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
c000000000337a10-c000000000337ff8: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffe0001bf5c4)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffe0001bf5c4-ffffffe0001bf9ca: stack_map_get_build_id_offset (STB_LOCAL)
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
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811fb8f0)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811fb8f0-ffffffff811fbdac: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811ee640)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811ee640-ffffffff811eeaf7: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f96c0)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811f96c0-ffffffff811f9b7c: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void stack_map_get_build_id_offset(struct bpf_stack_build_id *id_offs, u64 *ips, u32 trace_nr, bool user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81208160)
Location: kernel/bpf/stackmap.c:282
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81208160-ffffffff8120863a: stack_map_get_build_id_offset (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
