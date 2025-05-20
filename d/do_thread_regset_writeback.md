# Function: <code>do_thread_regset_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8126725b)
Location: fs/binfmt_elf.c:1612
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81269ded)
Location: fs/binfmt_elf.c:1612
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812949a1)
Location: fs/binfmt_elf.c:1620
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81297674)
Location: fs/binfmt_elf.c:1620
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812a965f)
Location: fs/binfmt_elf.c:1620
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812ac0cc)
Location: fs/binfmt_elf.c:1620
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b5fd9)
Location: fs/binfmt_elf.c:1679
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b9088)
Location: fs/binfmt_elf.c:1679
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d9878)
Location: fs/binfmt_elf.c:1693
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dc976)
Location: fs/binfmt_elf.c:1693
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81304114)
Location: fs/binfmt_elf.c:1707
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81307a23)
Location: fs/binfmt_elf.c:1707
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81319864)
Location: fs/binfmt_elf.c:1707
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d233)
Location: fs/binfmt_elf.c:1707
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8134252f)
Location: fs/binfmt_elf.c:1710
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81345e84)
Location: fs/binfmt_elf.c:1710
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8135a965)
Location: fs/binfmt_elf.c:1684
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e187)
Location: fs/binfmt_elf.c:1684
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139f854)
Location: fs/binfmt_elf.c:1804
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2d71)
Location: fs/binfmt_elf.c:1804
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b0357)
Location: fs/binfmt_elf.c:1712
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3d2e)
Location: fs/binfmt_elf.c:1712
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b755a)
Location: fs/binfmt_elf.c:1715
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813bacd9)
Location: fs/binfmt_elf.c:1715
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8140723a)
Location: fs/binfmt_elf.c:1717
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a9d9)
Location: fs/binfmt_elf.c:1717
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147bdcb)
Location: fs/binfmt_elf.c:1752
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f77e)
Location: fs/binfmt_elf.c:1752
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150e80b)
Location: fs/binfmt_elf.c:1747
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff815128ce)
Location: fs/binfmt_elf.c:1747
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81545fc2)
Location: fs/binfmt_elf.c:1752
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a303)
Location: fs/binfmt_elf.c:1752
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157b4ab)
Location: fs/binfmt_elf.c:1687
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f337)
Location: fs/binfmt_elf.c:1687
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041fffc)
Location: fs/binfmt_elf.c:1684
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010423b58)
Location: fs/binfmt_elf.c:1684
Inline: True
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
In fs/binfmt_elf.c (c05e856c)
Location: fs/binfmt_elf.c:1684
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052ef28)
Location: fs/binfmt_elf.c:1684
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000532b58)
Location: fs/binfmt_elf.c:1684
Inline: True
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
In fs/binfmt_elf.c (ffffffe0002c0fca)
Location: fs/binfmt_elf.c:1684
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81352f45)
Location: fs/binfmt_elf.c:1684
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81356767)
Location: fs/binfmt_elf.c:1684
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81343c25)
Location: fs/binfmt_elf.c:1684
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81347427)
Location: fs/binfmt_elf.c:1684
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81350a15)
Location: fs/binfmt_elf.c:1684
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81354237)
Location: fs/binfmt_elf.c:1684
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81363f9f)
Location: fs/binfmt_elf.c:1684
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81367a02)
Location: fs/binfmt_elf.c:1684
Inline: True
```
</details>
</li>
</ul>

## Differences
