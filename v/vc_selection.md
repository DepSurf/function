# Function: <code>vc_selection</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vc_selection(struct vc_data *vc, struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81747950)
Location: drivers/tty/vt/selection.c:316
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81747950-ffffffff81747a8c: vc_selection (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vc_selection(struct vc_data *vc, struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff817632a0)
Location: drivers/tty/vt/selection.c:316
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff817632a0-ffffffff817633d7: vc_selection (STB_LOCAL)
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
In drivers/tty/vt/selection.c (ffffffff81746faa)
Location: drivers/tty/vt/selection.c:316
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
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
In drivers/tty/vt/selection.c (ffffffff817c8004)
Location: drivers/tty/vt/selection.c:316
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
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
In drivers/tty/vt/selection.c (ffffffff819051a4)
Location: drivers/tty/vt/selection.c:316
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
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
In drivers/tty/vt/selection.c (ffffffff81a5f304)
Location: drivers/tty/vt/selection.c:317
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
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
In drivers/tty/vt/selection.c (ffffffff81aa99c4)
Location: drivers/tty/vt/selection.c:317
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
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
In drivers/tty/vt/selection.c (ffffffff81afc484)
Location: drivers/tty/vt/selection.c:317
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
