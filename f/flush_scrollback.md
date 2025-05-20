# Function: <code>flush_scrollback</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81589558)
Location: drivers/tty/vt/vt.c:632
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ee073)
Location: drivers/tty/vt/vt.c:634
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816275c9)
Location: drivers/tty/vt/vt.c:634
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff8164474a)
Location: drivers/tty/vt/vt.c:938
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff816780d6)
Location: drivers/tty/vt/vt.c:938
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff8169b636)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_scrollback(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e510)
Location: drivers/tty/vt/vt.c:945
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:csi_J
```
**Symbols:**

```
ffffffff8174e510-ffffffff8174e592: flush_scrollback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_scrollback(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81769ae0)
Location: drivers/tty/vt/vt.c:951
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:csi_J
```
**Symbols:**

```
ffffffff81769ae0-ffffffff81769b62: flush_scrollback (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffffffff8174de56)
Location: drivers/tty/vt/vt.c:951
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff817d0c24)
Location: drivers/tty/vt/vt.c:947
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff8190eb4b)
Location: drivers/tty/vt/vt.c:947
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff81a6a7cb)
Location: drivers/tty/vt/vt.c:947
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff81ab4ea6)
Location: drivers/tty/vt/vt.c:896
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff81b07b86)
Location: drivers/tty/vt/vt.c:895
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffff800010872c28)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (c09759e0)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (c0000000009138b8)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffe000544884)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff81661096)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff81641416)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff8168f476)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
In drivers/tty/vt/vt.c (ffffffff816a9a76)
Location: drivers/tty/vt/vt.c:939
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_J
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
</ul>
