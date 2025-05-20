# Function: <code>uprobe_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81187fe0)
Location: kernel/events/uprobes.c:870
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81187fe0-ffffffff81188272: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119a680)
Location: kernel/events/uprobes.c:872
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff8119a680-ffffffff8119a91b: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a9df0)
Location: kernel/events/uprobes.c:873
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811a9df0-ffffffff811aa08b: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b1400)
Location: kernel/events/uprobes.c:881
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811b1400-ffffffff811b1679: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c4fe0)
Location: kernel/events/uprobes.c:881
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811c4fe0-ffffffff811c5259: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e5520)
Location: kernel/events/uprobes.c:880
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811e5520-ffffffff811e57a2: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f61d0)
Location: kernel/events/uprobes.c:1156
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff811f61d0-ffffffff811f61e5: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120df70)
Location: kernel/events/uprobes.c:1144
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff8120df70-ffffffff8120df85: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121b5a0)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff8121b5a0-ffffffff8121b5b5: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247d60)
Location: kernel/events/uprobes.c:1195
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81247d60-ffffffff81247d75: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81252420)
Location: kernel/events/uprobes.c:1195
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81252420-ffffffff81252435: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81256380)
Location: kernel/events/uprobes.c:1193
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81256380-ffffffff81256395: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81292040)
Location: kernel/events/uprobes.c:1194
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81292040-ffffffff81292055: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e7880)
Location: kernel/events/uprobes.c:1189
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff812e7880-ffffffff812e78a1: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813513e0)
Location: kernel/events/uprobes.c:1192
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff813513e0-ffffffff81351401: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81382640)
Location: kernel/events/uprobes.c:1189
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81382640-ffffffff81382661: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aba20)
Location: kernel/events/uprobes.c:1189
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff813aba20-ffffffff813aba41: uprobe_register (STB_GLOBAL)
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
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a6ce8)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffff8000102a6ce8-ffff8000102a6d30: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d5e60)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
c04d5e60-c04d5e98: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000359fc0)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
c000000000359fc0-c000000000359fdc: uprobe_register (STB_GLOBAL)
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
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81213bf0)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81213bf0-ffffffff81213c05: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81206960)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81206960-ffffffff81206975: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81211990)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff81211990-ffffffff812119a5: uprobe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uprobe_register(struct inode *inode, loff_t offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812208e0)
Location: kernel/events/uprobes.c:1196
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
**Symbols:**

```
ffffffff812208e0-ffffffff812208f5: uprobe_register (STB_GLOBAL)
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
