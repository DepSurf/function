# Function: <code>i2c_check_addr_validity</code>

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
In drivers/i2c/i2c-core.c (ffffffff8167c640)
Location: drivers/i2c/i2c-core.c:871
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_device
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
In drivers/i2c/i2c-core.c (ffffffff816dd310)
Location: drivers/i2c/i2c-core.c:1004
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_device
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
In drivers/i2c/i2c-core.c (ffffffff8170d690)
Location: drivers/i2c/i2c-core.c:1141
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_addr_validity(unsigned int addr, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720b05)
Location: drivers/i2c/i2c-core-base.c:543
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
**Symbols:**

```
ffffffff81721da0-ffffffff81721dcc: i2c_check_addr_validity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_addr_validity(unsigned int addr, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791e55)
Location: drivers/i2c/i2c-core-base.c:548
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
**Symbols:**

```
ffffffff817931d0-ffffffff817931fc: i2c_check_addr_validity (STB_GLOBAL)
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
In drivers/i2c/i2c-core-base.c (ffffffff817d4857)
Location: drivers/i2c/i2c-core-base.c:529
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/i2c/i2c-core-base.c (ffffffff817fb9b7)
Location: drivers/i2c/i2c-core-base.c:541
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/i2c/i2c-core-base.c (ffffffff8183ca2e)
Location: drivers/i2c/i2c-core-base.c:539
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff8186e42e)
Location: drivers/i2c/i2c-core-base.c:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff8194221e)
Location: drivers/i2c/i2c-core-base.c:554
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff8194857d)
Location: drivers/i2c/i2c-core-base.c:682
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff8192beed)
Location: drivers/i2c/i2c-core-base.c:726
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff819cf0ad)
Location: drivers/i2c/i2c-core-base.c:727
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff81b30e58)
Location: drivers/i2c/i2c-core-base.c:728
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff81cc57d3)
Location: drivers/i2c/i2c-core-base.c:729
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff81d2d463)
Location: drivers/i2c/i2c-core-base.c:744
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff81de3382)
Location: drivers/i2c/i2c-core-base.c:747
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffff800010ab1af0)
Location: drivers/i2c/i2c-core-base.c:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (c0b93204)
Location: drivers/i2c/i2c-core-base.c:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (c000000000b9500c)
Location: drivers/i2c/i2c-core-base.c:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffe0006b98da)
Location: drivers/i2c/i2c-core-base.c:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818625be)
Location: drivers/i2c/i2c-core-base.c:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/i2c/i2c-core-base.c (ffffffff8187d81e)
Location: drivers/i2c/i2c-core-base.c:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
