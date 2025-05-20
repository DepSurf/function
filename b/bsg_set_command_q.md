# Function: <code>bsg_set_command_q</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814ee49b)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff815078fb)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bsg_set_command_q(struct bsg_device *bd, int *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815684f0)
Location: block/bsg.c:332
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff815684f0-ffffffff8156855f: bsg_set_command_q (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bsg_set_command_q(struct bsg_device *bd, int *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81582e30)
Location: block/bsg.c:334
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81582e30-ffffffff81582e9f: bsg_set_command_q (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bsg_set_command_q(struct bsg_device *bd, int *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81589c60)
Location: block/bsg.c:334
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81589c60-ffffffff81589ccf: bsg_set_command_q (STB_LOCAL)
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
In block/bsg.c (ffffffff815ef67c)
Location: block/bsg.c:90
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff816a0669)
Location: block/bsg.c:90
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff8175f179)
Location: block/bsg.c:90
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff8179e08e)
Location: block/bsg.c:92
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff817e1b0e)
Location: block/bsg.c:92
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffff80001060a428)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (c07b5158)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (c0000000007a6688)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffe000443544)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff814ffedb)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff814f03eb)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff814fbf6b)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
In block/bsg.c (ffffffff8151501b)
Location: block/bsg.c:332
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
