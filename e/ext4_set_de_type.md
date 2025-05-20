# Function: <code>ext4_set_de_type</code>

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
In fs/ext4/namei.c (ffffffff812a4e15)
Location: fs/ext4/ext4.h:3056
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
```
```
In fs/ext4/inline.c (ffffffff812e19c7)
Location: fs/ext4/ext4.h:3056
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
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
In fs/ext4/namei.c (ffffffff812d5a53)
Location: fs/ext4/ext4.h:3093
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
```
In fs/ext4/inline.c (ffffffff8131190d)
Location: fs/ext4/ext4.h:3093
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
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
In fs/ext4/namei.c (ffffffff812eb753)
Location: fs/ext4/ext4.h:3071
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
```
In fs/ext4/inline.c (ffffffff8132784d)
Location: fs/ext4/ext4.h:3071
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
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
In fs/ext4/inline.c (ffffffff812fb751)
Location: fs/ext4/ext4.h:3088
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8131b43c)
Location: fs/ext4/ext4.h:3088
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8131fedb)
Location: fs/ext4/ext4.h:3049
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8133faf3)
Location: fs/ext4/ext4.h:3049
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8134dfed)
Location: fs/ext4/ext4.h:3055
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8136daa3)
Location: fs/ext4/ext4.h:3055
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8136618d)
Location: fs/ext4/ext4.h:3082
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81385f23)
Location: fs/ext4/ext4.h:3082
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8138f510)
Location: fs/ext4/ext4.h:3169
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813aff03)
Location: fs/ext4/ext4.h:3169
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff813a7f6e)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c8ec3)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff813f4017)
Location: fs/ext4/ext4.h:3342
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81414a63)
Location: fs/ext4/ext4.h:3342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff814067a7)
Location: fs/ext4/ext4.h:3537
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff814280b3)
Location: fs/ext4/ext4.h:3537
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8140cc81)
Location: fs/ext4/ext4.h:3599
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8142ebc9)
Location: fs/ext4/ext4.h:3599
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8145fad1)
Location: fs/ext4/ext4.h:3667
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8148336d)
Location: fs/ext4/ext4.h:3667
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff814de0ba)
Location: fs/ext4/ext4.h:3629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815064cd)
Location: fs/ext4/ext4.h:3629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8157711a)
Location: fs/ext4/ext4.h:3641
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815a0f8d)
Location: fs/ext4/ext4.h:3641
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff815ae7ac)
Location: fs/ext4/ext4.h:3614
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815d790d)
Location: fs/ext4/ext4.h:3614
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff815e756c)
Location: fs/ext4/ext4.h:3632
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8160ff7d)
Location: fs/ext4/ext4.h:3632
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffff80001047b850)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffff8000104a09b0)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063d0cc)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c0662afc)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (c00000000059ed74)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c0000000005cceb8)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000305c44)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffe000322c04)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff813a054e)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c14a3)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff81390fde)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813b1f33)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff8139ddae)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813be953)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
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
In fs/ext4/inline.c (ffffffff813b231e)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813d3a33)
Location: fs/ext4/ext4.h:3231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
</ul>

## Differences
