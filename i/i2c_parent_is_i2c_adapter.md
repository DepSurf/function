# Function: <code>i2c_parent_is_i2c_adapter</code>

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
In drivers/i2c/i2c-core.c (ffffffff81678d8d)
Location: include/linux/i2c.h:537
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_lock_adapter
  - drivers/i2c/i2c-core.c:i2c_unlock_adapter
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core.c:i2c_trylock_adapter
```
```
In drivers/i2c/i2c-dev.c (ffffffff8167de15)
Location: include/linux/i2c.h:537
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/i2c/i2c-core.c (ffffffff816da198)
Location: include/linux/i2c.h:573
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff816df545)
Location: include/linux/i2c.h:573
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core.c (ffffffff8170a768)
Location: include/linux/i2c.h:595
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff8170f925)
Location: include/linux/i2c.h:595
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff8171efd8)
Location: include/linux/i2c.h:610
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81725b77)
Location: include/linux/i2c.h:610
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff81790288)
Location: include/linux/i2c.h:612
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81797010)
Location: include/linux/i2c.h:612
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff817d2d95)
Location: include/linux/i2c.h:701
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9bb8)
Location: include/linux/i2c.h:701
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff817f9e85)
Location: include/linux/i2c.h:709
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81800dd4)
Location: include/linux/i2c.h:709
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff8183abc8)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff818420e9)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff8186c558)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81873a69)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff81940265)
Location: include/linux/i2c.h:730
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81947c41)
Location: include/linux/i2c.h:730
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff819463d5)
Location: include/linux/i2c.h:738
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194da62)
Location: include/linux/i2c.h:738
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff81929c15)
Location: include/linux/i2c.h:746
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff819311f2)
Location: include/linux/i2c.h:746
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff819ccd65)
Location: include/linux/i2c.h:755
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d44c2)
Location: include/linux/i2c.h:755
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff81b2f8d5)
Location: include/linux/i2c.h:764
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_depth
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b3717b)
Location: include/linux/i2c.h:764
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff81cc3835)
Location: include/linux/i2c.h:766
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_depth
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccc59b)
Location: include/linux/i2c.h:766
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff81d2a085)
Location: include/linux/i2c.h:772
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d34303)
Location: include/linux/i2c.h:772
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff81ddff45)
Location: include/linux/i2c.h:765
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81dea3b3)
Location: include/linux/i2c.h:765
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffff800010aaf060)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab85fc)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (c0b90c08)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (c0b97f20)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (c000000000b91c40)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (c000000000b9b5a0)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffe0006b7738)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bd8ac)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818606e8)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81867bf9)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
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
In drivers/i2c/i2c-core-base.c (ffffffff8187b8f8)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
```
```
In drivers/i2c/i2c-dev.c (ffffffff81882ea9)
Location: include/linux/i2c.h:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
</details>
</li>
</ul>

## Differences
