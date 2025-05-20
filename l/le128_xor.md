# Function: <code>le128_xor</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8140e307)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/xts.c (ffffffff81436dbc)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/xts.c (ffffffff8146a18c)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/xts.c (ffffffff8148766f)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814b5360)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814ce41f)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff8152d74d)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff8154a6e1)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff81552d05)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff815b3d35)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff8165cb28)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff81716568)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff81751e38)
Location: include/crypto/b128ops.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffffffff81793cb8)
Location: include/crypto/b128ops.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
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
In crypto/xts.c (ffff8000105ca2f8)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (c0777ef0)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (c000000000754de4)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffe00040e8a8)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814c69ff)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814b741f)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814c2a8f)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
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
In crypto/xts.c (ffffffff814db55f)
Location: include/crypto/b128ops.h:75
Inline: True
Inline callers:
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
```
</details>
</li>
</ul>

## Differences
