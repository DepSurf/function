# Function: <code>trace_probe_cleanup</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cb890)
Location: kernel/trace/trace_probe.c:890
Inline: False
```
**Symbols:**

```
ffffffff811cb890-ffffffff811cb8fc: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7870)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
ffffffff811d7870-ffffffff811d78ba: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f4337)
Location: kernel/trace/trace_probe.c:977
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f41f0-ffffffff811f423a: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2ce7)
Location: kernel/trace/trace_probe.c:977
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f2ba0-ffffffff811f2bea: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3b67)
Location: kernel/trace/trace_probe.c:977
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff811f3a30-ffffffff811f3a7a: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81224e27)
Location: kernel/trace/trace_probe.c:1009
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff81224cf0-ffffffff81224d3a: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264cd6)
Location: kernel/trace/trace_probe.c:1016
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff81264b70-ffffffff81264bc4: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6866)
Location: kernel/trace/trace_probe.c:1039
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff812b66f0-ffffffff812b6744: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9d56)
Location: kernel/trace/trace_probe.c:1520
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
**Symbols:**

```
ffffffff812d9be0-ffffffff812d9c34: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f7cb6)
Location: kernel/trace/trace_probe.c:1757
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_init
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
**Symbols:**

```
ffffffff812f7b40-ffffffff812f7b94: trace_probe_cleanup (STB_GLOBAL)
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
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010257be0)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
ffff800010257be0-ffff800010257c44: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048ad38)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
c048ad38-c048ad90: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f9b80)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
c0000000002f9b80-c0000000002f9c0c: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cfe90)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
ffffffff811cfe90-ffffffff811cfeda: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2c60)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
ffffffff811c2c60-ffffffff811c2caa: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cdc60)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
ffffffff811cdc60-ffffffff811cdcaa: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_probe_cleanup(struct trace_probe *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dbec0)
Location: kernel/trace/trace_probe.c:977
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_init
```
**Symbols:**

```
ffffffff811dbec0-ffffffff811dbf0a: trace_probe_cleanup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
