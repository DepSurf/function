# Function: <code>delayed_uprobe_delete</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f49f0)
Location: kernel/events/uprobes.c:323
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff811f49f0-ffffffff811f4a2e: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:311
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff8120c6e0-ffffffff8120c71c: delayed_uprobe_delete (STB_LOCAL)
ffffffff8120f628-ffffffff8120f63b: delayed_uprobe_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812199d0)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff812199d0-ffffffff81219a0b: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81245710)
Location: kernel/events/uprobes.c:314
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
```
**Symbols:**

```
ffffffff81245710-ffffffff8124574b: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8124fd30)
Location: kernel/events/uprobes.c:314
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
```
**Symbols:**

```
ffffffff8124fd30-ffffffff8124fd6b: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81254610)
Location: kernel/events/uprobes.c:314
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81254610-ffffffff8125464b: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8129269e)
Location: kernel/events/uprobes.c:314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e7ff2)
Location: kernel/events/uprobes.c:308
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81351d22)
Location: kernel/events/uprobes.c:310
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81382c2f)
Location: kernel/events/uprobes.c:309
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813abfff)
Location: kernel/events/uprobes.c:309
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a4bb0)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffff8000102a4bb0-ffff8000102a4c10: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d4214)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
c04d4214-c04d4270: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000357510)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:delayed_uprobe_remove
```
**Symbols:**

```
c000000000357510-c000000000357598: delayed_uprobe_delete (STB_LOCAL)
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
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81212020)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81212020-ffffffff8121205b: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81204db0)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81204db0-ffffffff81204deb: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120fdc0)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff8120fdc0-ffffffff8120fdfb: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe *du);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121ed90)
Location: kernel/events/uprobes.c:320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff8121ed90-ffffffff8121edcb: delayed_uprobe_delete (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
