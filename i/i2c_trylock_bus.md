# Function: <code>i2c_trylock_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b7fb)
Location: include/linux/i2c.h:634
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff8172084f)
Location: include/linux/i2c.h:649
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff81791b83)
Location: include/linux/i2c.h:651
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff817d45a3)
Location: include/linux/i2c.h:740
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff817fb723)
Location: include/linux/i2c.h:748
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff8183c4f6)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f453)
Location: include/linux/i2c.h:767
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
In drivers/i2c/i2c-core-base.c (ffffffff8186def6)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870df3)
Location: include/linux/i2c.h:767
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
In drivers/i2c/i2c-core-base.c (ffffffff81941fed)
Location: include/linux/i2c.h:769
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944e33)
Location: include/linux/i2c.h:769
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff8194833d)
Location: include/linux/i2c.h:777
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194ae73)
Location: include/linux/i2c.h:777
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff8192bc9d)
Location: include/linux/i2c.h:785
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e9b3)
Location: include/linux/i2c.h:785
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff819cee5d)
Location: include/linux/i2c.h:794
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1be3)
Location: include/linux/i2c.h:794
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff81b30b94)
Location: include/linux/i2c.h:803
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b341c4)
Location: include/linux/i2c.h:803
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff81cc54c4)
Location: include/linux/i2c.h:805
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc91b8)
Location: include/linux/i2c.h:805
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff81d2d154)
Location: include/linux/i2c.h:811
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30ed8)
Location: include/linux/i2c.h:811
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff81de3093)
Location: include/linux/i2c.h:804
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6e3f)
Location: include/linux/i2c.h:804
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffff800010ab1858)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab49fc)
Location: include/linux/i2c.h:767
Inline: True
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
In drivers/i2c/i2c-core-base.c (c0b92888)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c0b95c14)
Location: include/linux/i2c.h:767
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
In drivers/i2c/i2c-core-base.c (c000000000b946f4)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b98c10)
Location: include/linux/i2c.h:767
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffe0006b9286)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbebc)
Location: include/linux/i2c.h:767
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff81862086)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864f83)
Location: include/linux/i2c.h:767
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
In drivers/i2c/i2c-core-base.c (ffffffff8187d2e6)
Location: include/linux/i2c.h:767
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880233)
Location: include/linux/i2c.h:767
Inline: True
```
</details>
</li>
</ul>

## Differences
