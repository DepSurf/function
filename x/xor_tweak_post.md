# Function: <code>xor_tweak_post</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81487702)
Location: crypto/xts.c:131
Inline: True
Inline callers:
  - crypto/xts.c:crypt_done
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
In crypto/xts.c (ffffffff814b53fc)
Location: crypto/xts.c:127
Inline: True
Inline callers:
  - crypto/xts.c:crypt_done
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
In crypto/xts.c (ffffffff814ce5cc)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (ffffffff8152d955)
Location: crypto/xts.c:136
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In crypto/xts.c (ffff8000105ca438)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (c0778078)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (c000000000754f98)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (ffffffe00040e9a0)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (ffffffff814c6bac)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (ffffffff814b75cc)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (ffffffff814c2c3c)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/xts.c (ffffffff814db70c)
Location: crypto/xts.c:142
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
</details>
</li>
</ul>

## Differences
