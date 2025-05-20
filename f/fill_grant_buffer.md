# Function: <code>fill_grant_buffer</code>

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
In drivers/block/xen-blkfront.c (ffffffff81576c5f)
Location: drivers/block/xen-blkfront.c:226
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff815cca58)
Location: drivers/block/xen-blkfront.c:285
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff815f9618)
Location: drivers/block/xen-blkfront.c:285
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff8160d754)
Location: drivers/block/xen-blkfront.c:289
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff81675fd4)
Location: drivers/block/xen-blkfront.c:289
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff816b190a)
Location: drivers/block/xen-blkfront.c:289
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff816d240a)
Location: drivers/block/xen-blkfront.c:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff8170a89a)
Location: drivers/block/xen-blkfront.c:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff8172eb9a)
Location: drivers/block/xen-blkfront.c:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fill_grant_buffer(struct blkfront_ring_info *rinfo, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817ec9b0)
Location: drivers/block/xen-blkfront.c:299
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
**Symbols:**

```
ffffffff817ec9b0-ffffffff817ecb0f: fill_grant_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fill_grant_buffer(struct blkfront_ring_info *rinfo, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff818012e0)
Location: drivers/block/xen-blkfront.c:299
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
**Symbols:**

```
ffffffff818012e0-ffffffff8180143f: fill_grant_buffer (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffffffff817e5f7e)
Location: drivers/block/xen-blkfront.c:299
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff8187231e)
Location: drivers/block/xen-blkfront.c:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff819ba4ee)
Location: drivers/block/xen-blkfront.c:306
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff81b2fa0e)
Location: drivers/block/xen-blkfront.c:309
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff81b82e53)
Location: drivers/block/xen-blkfront.c:309
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff81bd6d44)
Location: drivers/block/xen-blkfront.c:309
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffff800010925b44)
Location: drivers/block/xen-blkfront.c:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f4b0a)
Location: drivers/block/xen-blkfront.c:303
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8172205a)
Location: drivers/block/xen-blkfront.c:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
In drivers/block/xen-blkfront.c (ffffffff8173d49a)
Location: drivers/block/xen-blkfront.c:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
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
