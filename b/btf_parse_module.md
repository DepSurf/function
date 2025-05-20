# Function: <code>btf_parse_module</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct btf *btf_parse_module(const char *module_name, const void *data, unsigned int data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223fb0)
Location: kernel/bpf/btf.c:4488
Inline: False
```
**Symbols:**

```
ffffffff81223fb0-ffffffff81224169: btf_parse_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct btf *btf_parse_module(const char *module_name, const void *data, unsigned int data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81228a80)
Location: kernel/bpf/btf.c:4559
Inline: False
```
**Symbols:**

```
ffffffff81228a80-ffffffff81228c39: btf_parse_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct btf *btf_parse_module(const char *module_name, const void *data, unsigned int data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81260d70)
Location: kernel/bpf/btf.c:4607
Inline: False
```
**Symbols:**

```
ffffffff81260d70-ffffffff81260f29: btf_parse_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct btf *btf_parse_module(const char *module_name, const void *data, unsigned int data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ac3e0)
Location: kernel/bpf/btf.c:5122
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff812ac3e0-ffffffff812ac60e: btf_parse_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct btf *btf_parse_module(const char *module_name, const void *data, unsigned int data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130bd60)
Location: kernel/bpf/btf.c:5710
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff8130bd60-ffffffff8130bf8e: btf_parse_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct btf *btf_parse_module(const char *module_name, const void *data, unsigned int data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133adc0)
Location: kernel/bpf/btf.c:5788
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff8133adc0-ffffffff8133afee: btf_parse_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct btf *btf_parse_module(const char *module_name, const void *data, unsigned int data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81360ef0)
Location: kernel/bpf/btf.c:5958
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff81360ef0-ffffffff8136117c: btf_parse_module (STB_LOCAL)
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
