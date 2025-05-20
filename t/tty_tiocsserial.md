# Function: <code>tty_tiocsserial</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162eb04)
Location: drivers/tty/tty_io.c:2480
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff8166269c)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81684d0c)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_tiocsserial(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733670)
Location: drivers/tty/tty_io.c:2483
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81733670-ffffffff81733749: tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_tiocsserial(struct tty_struct *tty, struct serial_struct *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8174f7b0)
Location: drivers/tty/tty_io.c:2571
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8174f7b0-ffffffff8174f889: tty_tiocsserial (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81736dc6)
Location: drivers/tty/tty_io.c:2644
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff817b779f)
Location: drivers/tty/tty_io.c:2642
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff818f2c54)
Location: drivers/tty/tty_io.c:2615
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81a4b287)
Location: drivers/tty/tty_io.c:2614
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81a94fa1)
Location: drivers/tty/tty_io.c:2623
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81ae7991)
Location: drivers/tty/tty_io.c:2640
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffff8000108528b8)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (c095d12c)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (c0000000008f1444)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffe00052f62c)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff8164a78c)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff8162abdc)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81678b4c)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81692787)
Location: drivers/tty/tty_io.c:2484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
