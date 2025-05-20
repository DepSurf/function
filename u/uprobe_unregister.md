# Function: <code>uprobe_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81188280)
Location: kernel/events/uprobes.c:945
Inline: False
```
**Symbols:**

```
ffffffff81188280-ffffffff811882e4: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119a920)
Location: kernel/events/uprobes.c:947
Inline: False
```
**Symbols:**

```
ffffffff8119a920-ffffffff8119a984: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811aa090)
Location: kernel/events/uprobes.c:948
Inline: False
```
**Symbols:**

```
ffffffff811aa090-ffffffff811aa0f4: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b1680)
Location: kernel/events/uprobes.c:956
Inline: False
```
**Symbols:**

```
ffffffff811b1680-ffffffff811b16d5: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c5260)
Location: kernel/events/uprobes.c:956
Inline: False
```
**Symbols:**

```
ffffffff811c5260-ffffffff811c52b5: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e57b0)
Location: kernel/events/uprobes.c:955
Inline: False
```
**Symbols:**

```
ffffffff811e57b0-ffffffff811e5800: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f5eb0)
Location: kernel/events/uprobes.c:1079
Inline: False
```
**Symbols:**

```
ffffffff811f5eb0-ffffffff811f5f00: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1067
Inline: False
```
**Symbols:**

```
ffffffff8120f6f9-ffffffff8120f70c: uprobe_unregister.cold (STB_LOCAL)
ffffffff8120dc30-ffffffff8120dc82: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121b260)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff8121b260-ffffffff8121b2b8: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247b70)
Location: kernel/events/uprobes.c:1109
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff81247b70-ffffffff81247bef: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81252240)
Location: kernel/events/uprobes.c:1109
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff81252240-ffffffff812522bf: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812561c0)
Location: kernel/events/uprobes.c:1107
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff812561c0-ffffffff81256218: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291e70)
Location: kernel/events/uprobes.c:1108
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff81291e70-ffffffff81291ec8: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e7650)
Location: kernel/events/uprobes.c:1102
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff812e7650-ffffffff812e76e1: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81351190)
Location: kernel/events/uprobes.c:1105
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff81351190-ffffffff81351221: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81382400)
Location: kernel/events/uprobes.c:1102
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff81382400-ffffffff81382491: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813ab7e0)
Location: kernel/events/uprobes.c:1102
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_unregister
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff813ab7e0-ffffffff813ab871: uprobe_unregister (STB_GLOBAL)
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
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a6938)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffff8000102a6938-ffff8000102a69bc: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d5a98)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
c04d5a98-c04d5b00: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000359a90)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
c000000000359a90-c000000000359b34: uprobe_unregister (STB_GLOBAL)
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
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812138b0)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff812138b0-ffffffff81213908: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81206620)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff81206620-ffffffff81206678: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81211650)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff81211650-ffffffff812116a8: uprobe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uprobe_unregister(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812205a0)
Location: kernel/events/uprobes.c:1119
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:__probe_event_disable
```
**Symbols:**

```
ffffffff812205a0-ffffffff812205f8: uprobe_unregister (STB_GLOBAL)
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
