# Function: <code>ext4_mb_discard_preallocations</code>

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
In fs/ext4/mballoc.c (ffffffff812d44b9)
Location: fs/ext4/mballoc.c:4390
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff81303e04)
Location: fs/ext4/mballoc.c:4404
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff81319dc4)
Location: fs/ext4/mballoc.c:4411
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813111d0)
Location: fs/ext4/mballoc.c:4472
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff81335d8e)
Location: fs/ext4/mballoc.c:4472
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff8136407c)
Location: fs/ext4/mballoc.c:4442
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff8137c31e)
Location: fs/ext4/mballoc.c:4441
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813a638f)
Location: fs/ext4/mballoc.c:4442
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813bf1ff)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_mb_discard_preallocations(struct super_block *sb, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81407a90)
Location: fs/ext4/mballoc.c:4671
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81407a90-ffffffff81407b42: ext4_mb_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_mb_discard_preallocations(struct super_block *sb, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141a010)
Location: fs/ext4/mballoc.c:4850
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff8141a010-ffffffff8141a0b3: ext4_mb_discard_preallocations (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff81425030)
Location: fs/ext4/mballoc.c:5383
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff814738e3)
Location: fs/ext4/mballoc.c:5439
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
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
In fs/ext4/mballoc.c (ffffffff814f5073)
Location: fs/ext4/mballoc.c:5494
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
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
In fs/ext4/mballoc.c (ffffffff8158f334)
Location: fs/ext4/mballoc.c:5465
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
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
In fs/ext4/mballoc.c (ffffffff815c5fb4)
Location: fs/ext4/mballoc.c:6039
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
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
In fs/ext4/mballoc.c (ffffffff81600724)
Location: fs/ext4/mballoc.c:5999
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
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
In fs/ext4/mballoc.c (ffff800010495f30)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (c0657b68)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (c0000000005bfd14)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffe00031aa86)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813b77df)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813a826f)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813b503f)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813c9c8e)
Location: fs/ext4/mballoc.c:4461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
