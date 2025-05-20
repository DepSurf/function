# Function: <code>btf_parse</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c882e)
Location: kernel/bpf/btf.c:2146
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dc67e)
Location: kernel/bpf/btf.c:2797
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1dd0)
Location: kernel/bpf/btf.c:3287
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fe4e0)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct btf *btf_parse(void *btf_data, u32 btf_data_size, u32 log_level, char *log_ubuf, u32 log_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224590)
Location: kernel/bpf/btf.c:3396
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff81224590-ffffffff8122485f: btf_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct btf *btf_parse(void *btf_data, u32 btf_data_size, u32 log_level, char *log_ubuf, u32 log_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122ae10)
Location: kernel/bpf/btf.c:4187
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff8122ae10-ffffffff8122b0e6: btf_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct btf *btf_parse(void *btf_data, u32 btf_data_size, u32 log_level, char *log_ubuf, u32 log_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122f800)
Location: kernel/bpf/btf.c:4260
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff8122f800-ffffffff8122fad0: btf_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct btf *btf_parse(bpfptr_t btf_data, u32 btf_data_size, u32 log_level, char *log_ubuf, u32 log_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81268560)
Location: kernel/bpf/btf.c:4309
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff81268560-ffffffff81268856: btf_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct btf *btf_parse(bpfptr_t btf_data, u32 btf_data_size, u32 log_level, char *log_ubuf, u32 log_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b57f0)
Location: kernel/bpf/btf.c:4856
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff812b57f0-ffffffff812b5b2c: btf_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct btf *btf_parse(bpfptr_t btf_data, u32 btf_data_size, u32 log_level, char *log_ubuf, u32 log_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131a720)
Location: kernel/bpf/btf.c:5395
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff8131a720-ffffffff8131ab54: btf_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct btf *btf_parse(const union bpf_attr *attr, bpfptr_t uattr, u32 uattr_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81349d80)
Location: kernel/bpf/btf.c:5473
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff81349d80-ffffffff8134a238: btf_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct btf *btf_parse(const union bpf_attr *attr, bpfptr_t uattr, u32 uattr_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813704d0)
Location: kernel/bpf/btf.c:5481
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff813704d0-ffffffff813709e6: btf_parse (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010285524)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b5b04)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c0000000003302f0)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001ba932)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f6b00)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e9850)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f48d0)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81202de0)
Location: kernel/bpf/btf.c:3286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *btf_data</code> ➡️ <code>bpfptr_t btf_data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const union bpf_attr *attr</code>
</li>
<li>
<b>Param added. </b>
<code>bpfptr_t uattr</code>
</li>
<li>
<b>Param added. </b>
<code>u32 uattr_size</code>
</li>
<li>
<b>Param removed. </b>
<code>bpfptr_t btf_data</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 btf_data_size</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 log_level</code>
</li>
<li>
<b>Param removed. </b>
<code>char *log_ubuf</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 log_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
