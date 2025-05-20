# Function: <code>dio_await_one</code>

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
In fs/direct-io.c (ffffffff8124b9f8)
Location: fs/direct-io.c:431
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff812748c4)
Location: fs/direct-io.c:439
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81287cee)
Location: fs/direct-io.c:442
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81295874)
Location: fs/direct-io.c:443
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff812b89cf)
Location: fs/direct-io.c:482
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff812e12c1)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff812f5ee4)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81317054)
Location: fs/direct-io.c:504
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81329ed2)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *dio_await_one(struct dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813620e0)
Location: fs/direct-io.c:484
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff813620e0-ffffffff8136219d: dio_await_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *dio_await_one(struct dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8136ef40)
Location: fs/direct-io.c:465
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff8136ef40-ffffffff8136effa: dio_await_one (STB_LOCAL)
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
In fs/direct-io.c (ffffffff813776d1)
Location: fs/direct-io.c:467
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff813c3c4f)
Location: fs/direct-io.c:467
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff8144aac8)
Location: fs/direct-io.c:459
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
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
In fs/direct-io.c (ffffffff814d9208)
Location: fs/direct-io.c:459
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81511f8f)
Location: fs/direct-io.c:465
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81546433)
Location: fs/direct-io.c:465
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
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
In fs/direct-io.c (ffff8000103e50d8)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (c05bd094)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (c0000000004eb4c0)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffe00029ac12)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff813224b2)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81313052)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff8131ff82)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/direct-io.c (ffffffff81331ca2)
Location: fs/direct-io.c:503
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
