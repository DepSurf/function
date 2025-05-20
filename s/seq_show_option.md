# Function: <code>seq_show_option</code>

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
In kernel/cgroup.c (ffffffff81115d8f)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
```
```
In fs/ext4/super.c (ffffffff812ad5ef)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup.c (ffffffff8111ae24)
Location: include/linux/seq_file.h:158
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
```
```
In fs/ext4/super.c (ffffffff812e1fc3)
Location: include/linux/seq_file.h:158
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup.c (ffffffff81122f84)
Location: include/linux/seq_file.h:158
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
```
```
In fs/ext4/super.c (ffffffff812f7b73)
Location: include/linux/seq_file.h:158
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff81129ada)
Location: include/linux/seq_file.h:158
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff8132c4fa)
Location: include/linux/seq_file.h:158
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff811368aa)
Location: include/linux/seq_file.h:159
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813509ba)
Location: include/linux/seq_file.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff811451bd)
Location: include/linux/seq_file.h:178
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff8137ec94)
Location: include/linux/seq_file.h:178
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff81150bfd)
Location: include/linux/seq_file.h:178
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813974eb)
Location: include/linux/seq_file.h:178
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115cb3d)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813c143f)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116873d)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813da79e)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8117a44d)
Location: include/linux/seq_file.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff81426a83)
Location: include/linux/seq_file.h:210
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8117724d)
Location: include/linux/seq_file.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff8143e13a)
Location: include/linux/seq_file.h:211
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff81177ded)
Location: include/linux/seq_file.h:215
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff81443f79)
Location: include/linux/seq_file.h:215
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8119f74d)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff81497d79)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff811cfc9d)
Location: include/linux/seq_file.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff81524106)
Location: include/linux/seq_file.h:239
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8121369d)
Location: include/linux/seq_file.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff815c177c)
Location: include/linux/seq_file.h:239
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff81228fad)
Location: include/linux/seq_file.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff815f8ee4)
Location: include/linux/seq_file.h:239
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff81240dfd)
Location: include/linux/seq_file.h:254
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff81631a6e)
Location: include/linux/seq_file.h:254
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffff8000101db278)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffff8000104adf44)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (c041da20)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (c0676b34)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (c000000000248460)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (c0000000005e6bd8)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffe000153856)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffe00033108c)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff81160d5d)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813d2d7e)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff81153fcd)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813c37fe)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115eb2d)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813d020e)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116bdad)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/ext4/super.c (ffffffff813e5804)
Location: include/linux/seq_file.h:179
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
</details>
</li>
</ul>

## Differences
