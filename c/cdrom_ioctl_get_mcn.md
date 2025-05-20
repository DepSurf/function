# Function: <code>cdrom_ioctl_get_mcn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81602059)
Location: drivers/cdrom/cdrom.c:2502
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81661de2)
Location: drivers/cdrom/cdrom.c:2512
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168fbd2)
Location: drivers/cdrom/cdrom.c:2512
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a4de7)
Location: drivers/cdrom/cdrom.c:2518
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8171014f)
Location: drivers/cdrom/cdrom.c:2518
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8174ed78)
Location: drivers/cdrom/cdrom.c:2515
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81773176)
Location: drivers/cdrom/cdrom.c:2518
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817b0c4d)
Location: drivers/cdrom/cdrom.c:2519
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817e0f9d)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdrom_ioctl_get_mcn(struct cdrom_device_info *cdi, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ace80)
Location: drivers/cdrom/cdrom.c:2538
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818ace80-ffffffff818acf5a: cdrom_ioctl_get_mcn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_ioctl_get_mcn(struct cdrom_device_info *cdi, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bbac0)
Location: drivers/cdrom/cdrom.c:2521
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818bbac0-ffffffff818bbb9a: cdrom_ioctl_get_mcn (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffff818a1c68)
Location: drivers/cdrom/cdrom.c:2521
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81936615)
Location: drivers/cdrom/cdrom.c:2466
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81a8d4ff)
Location: drivers/cdrom/cdrom.c:2505
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81c0ea6d)
Location: drivers/cdrom/cdrom.c:2505
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81c7689a)
Location: drivers/cdrom/cdrom.c:2491
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81d2b29a)
Location: drivers/cdrom/cdrom.c:2491
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffff800010a0f254)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (c0ae7660)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (c000000000ac5b4c)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffe0006351f4)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8179937d)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8178b04d)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817d5e1d)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817f00bd)
Location: drivers/cdrom/cdrom.c:2526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
