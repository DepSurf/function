# Function: <code>eventfd_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void eventfd_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812590c0)
Location: fs/eventfd.c:75
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff812590c0-ffffffff812590d0: eventfd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void eventfd_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81281c6f)
Location: fs/eventfd.c:75
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff81281aa0-ffffffff81281ab0: eventfd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void eventfd_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8129579f)
Location: fs/eventfd.c:75
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
**Symbols:**

```
ffffffff812955d0-ffffffff812955e0: eventfd_free (STB_LOCAL)
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
In fs/eventfd.c (ffffffff812a28a0)
Location: fs/eventfd.c:75
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_put
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
In fs/eventfd.c (ffffffff812c5d24)
Location: fs/eventfd.c:75
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff812eeff4)
Location: fs/eventfd.c:75
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81303984)
Location: fs/eventfd.c:75
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81324f48)
Location: fs/eventfd.c:82
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81337cd8)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81371a27)
Location: fs/eventfd.c:98
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8137f7e7)
Location: fs/eventfd.c:98
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81386467)
Location: fs/eventfd.c:98
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff813d3737)
Location: fs/eventfd.c:96
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8145cfaf)
Location: fs/eventfd.c:96
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff814ec73f)
Location: fs/eventfd.c:101
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8152368f)
Location: fs/eventfd.c:101
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81557dbf)
Location: fs/eventfd.c:89
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffff8000103f5be0)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_put
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
In fs/eventfd.c (c05ca7c4)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_put
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
In fs/eventfd.c (c0000000004fdd44)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_put
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
In fs/eventfd.c (ffffffe0002a680c)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff813302b8)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81320ed8)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff8132dd88)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
In fs/eventfd.c (ffffffff81340b68)
Location: fs/eventfd.c:97
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
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
</ul>
