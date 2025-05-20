# Function: <code>tun_ring_recv</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164e725)
Location: drivers/net/tun.c:1441
Inline: True
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
In drivers/net/tun.c (ffffffff81680435)
Location: drivers/net/tun.c:1432
Inline: True
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
In drivers/net/tun.c (ffffffff81695a18)
Location: drivers/net/tun.c:1469
Inline: True
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
In drivers/net/tun.c (ffffffff8170055f)
Location: drivers/net/tun.c:1916
Inline: True
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
In drivers/net/tun.c (ffffffff8173ff5f)
Location: drivers/net/tun.c:2145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff81763f79)
Location: drivers/net/tun.c:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff817a1ccb)
Location: drivers/net/tun.c:2158
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff817c299b)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff8188ec3d)
Location: drivers/net/tun.c:2137
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *tun_ring_recv(struct tun_file *tfile, int noblock, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189b860)
Location: drivers/net/tun.c:2059
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff8189b860-ffffffff8189bb2a: tun_ring_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *tun_ring_recv(struct tun_file *tfile, int noblock, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187efe0)
Location: drivers/net/tun.c:2064
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff8187efe0-ffffffff8187f2b8: tun_ring_recv (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8191100d)
Location: drivers/net/tun.c:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *tun_ring_recv(struct tun_file *tfile, int noblock, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a613b0)
Location: drivers/net/tun.c:2152
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81a613b0-ffffffff81a61699: tun_ring_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *tun_ring_recv(struct tun_file *tfile, int noblock, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bec710)
Location: drivers/net/tun.c:2156
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81bec710-ffffffff81bec9f9: tun_ring_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *tun_ring_recv(struct tun_file *tfile, int noblock, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c44c10)
Location: drivers/net/tun.c:2170
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81c44c10-ffffffff81c44ef9: tun_ring_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *tun_ring_recv(struct tun_file *tfile, int noblock, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfa770)
Location: drivers/net/tun.c:2182
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81cfa770-ffffffff81cfaa59: tun_ring_recv (STB_LOCAL)
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
In drivers/net/tun.c (ffff8000109dd4a4)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (c0ac5ca4)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (c000000000aa3bf0)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffe0006286f2)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff8178746b)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff81766dbb)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff817b781b)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
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
In drivers/net/tun.c (ffffffff817d1ec9)
Location: drivers/net/tun.c:2162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
