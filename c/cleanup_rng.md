# Function: <code>cleanup_rng</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cleanup_rng(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8151a450)
Location: drivers/char/hw_random/core.c:97
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
**Symbols:**

```
ffffffff8151a450-ffffffff8151a473: cleanup_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cleanup_rng(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8156d254)
Location: drivers/char/hw_random/core.c:97
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
**Symbols:**

```
ffffffff8156d140-ffffffff8156d163: cleanup_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cleanup_rng(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff815999c4)
Location: drivers/char/hw_random/core.c:97
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
**Symbols:**

```
ffffffff815998b0-ffffffff815998d3: cleanup_rng (STB_LOCAL)
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
In drivers/char/hw_random/core.c (ffffffff815ad9f3)
Location: drivers/char/hw_random/core.c:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff816143ea)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff8164e0d9)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff8166c259)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff816a1e29)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff816c4b89)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff81779317)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff81793b77)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff81776757)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff817fc717)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
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
In drivers/char/hw_random/core.c (ffffffff8193b471)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
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
In drivers/char/hw_random/core.c (ffffffff81a9bbd1)
Location: drivers/char/hw_random/core.c:78
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
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
In drivers/char/hw_random/core.c (ffffffff81ae7531)
Location: drivers/char/hw_random/core.c:78
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
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
In drivers/char/hw_random/core.c (ffffffff81b3a901)
Location: drivers/char/hw_random/core.c:80
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
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
In drivers/char/hw_random/core.c (ffff8000108b6ea0)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (c09b08a4)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (c000000000950d40)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
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
In drivers/char/hw_random/core.c (ffffffe000567a52)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff8168a5d9)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff81667fd9)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff816b8849)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
In drivers/char/hw_random/core.c (ffffffff816d2e19)
Location: drivers/char/hw_random/core.c:76
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
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
