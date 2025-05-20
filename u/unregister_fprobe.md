# Function: <code>unregister_fprobe</code>

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
int unregister_fprobe(struct fprobe *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812684b0)
Location: kernel/trace/fprobe.c:300
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_release
```
**Symbols:**

```
ffffffff812684b0-ffffffff81268506: unregister_fprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_fprobe(struct fprobe *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812ba6c0)
Location: kernel/trace/fprobe.c:302
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_release
```
**Symbols:**

```
ffffffff812ba6c0-ffffffff812ba721: unregister_fprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int unregister_fprobe(struct fprobe *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812de1f0)
Location: kernel/trace/fprobe.c:375
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_release
```
**Symbols:**

```
ffffffff812de1f0-ffffffff812de282: unregister_fprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int unregister_fprobe(struct fprobe *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812fc2e0)
Location: kernel/trace/fprobe.c:365
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_release
```
**Symbols:**

```
ffffffff812fc2e0-ffffffff812fc388: unregister_fprobe (STB_GLOBAL)
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
