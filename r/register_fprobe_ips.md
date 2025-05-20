# Function: <code>register_fprobe_ips</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_fprobe_ips(struct fprobe *fp, long unsigned int *addrs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff81268a00)
Location: kernel/trace/fprobe.c:238
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:register_fprobe_syms
```
**Symbols:**

```
ffffffff81268a00-ffffffff81268aea: register_fprobe_ips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_fprobe_ips(struct fprobe *fp, long unsigned int *addrs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812babf0)
Location: kernel/trace/fprobe.c:240
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:register_fprobe_syms
```
**Symbols:**

```
ffffffff812babf0-ffffffff812bacda: register_fprobe_ips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_fprobe_ips(struct fprobe *fp, long unsigned int *addrs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812de530)
Location: kernel/trace/fprobe.c:305
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:register_fprobe_syms
```
**Symbols:**

```
ffffffff812de530-ffffffff812de61a: register_fprobe_ips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_fprobe_ips(struct fprobe *fp, long unsigned int *addrs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812fc6a0)
Location: kernel/trace/fprobe.c:295
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:register_fprobe_syms
```
**Symbols:**

```
ffffffff812fc6a0-ffffffff812fc796: register_fprobe_ips (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
