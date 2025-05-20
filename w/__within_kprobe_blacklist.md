# Function: <code>__within_kprobe_blacklist</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81176040)
Location: kernel/kprobes.c:1384
Inline: True
```
**Symbols:**

```
ffffffff81176040-ffffffff8117607a: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81181ef0)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
ffffffff81181ef0-ffffffff81181f2a: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81197416)
Location: kernel/kprobes.c:1469
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194526)
Location: kernel/kprobes.c:1433
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81195556)
Location: kernel/kprobes.c:1434
Inline: True
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
In kernel/kprobes.c (ffffffff811be4b6)
Location: kernel/kprobes.c:1426
Inline: True
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
In kernel/kprobes.c (ffffffff811f1809)
Location: kernel/kprobes.c:1383
Inline: True
Inline callers:
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
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
In kernel/kprobes.c (ffffffff81238449)
Location: kernel/kprobes.c:1380
Inline: True
Inline callers:
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
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
In kernel/kprobes.c (ffffffff8124f529)
Location: kernel/kprobes.c:1380
Inline: True
Inline callers:
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
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
In kernel/kprobes.c (ffffffff81269459)
Location: kernel/kprobes.c:1380
Inline: True
Inline callers:
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/kprobes.c:within_kprobe_blacklist
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffff8000101f7720)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
ffff8000101f7720-ffff8000101f7794: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c043761c)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
c043761c-c0437678: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c00000000026d9e0)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
c00000000026d9e0-c00000000026da48: __within_kprobe_blacklist.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8117a510)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
ffffffff8117a510-ffffffff8117a54a: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8116d6b0)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
ffffffff8116d6b0-ffffffff8116d6ea: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811782e0)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
ffffffff811782e0-ffffffff8117831a: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81185bb0)
Location: kernel/kprobes.c:1429
Inline: True
```
**Symbols:**

```
ffffffff81185bb0-ffffffff81185bea: __within_kprobe_blacklist.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
