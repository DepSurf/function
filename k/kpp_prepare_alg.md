# Function: <code>kpp_prepare_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (ffffffff813e0466)
Location: crypto/kpp.c:98
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff813f89e6)
Location: crypto/kpp.c:98
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff81404ed6)
Location: crypto/kpp.c:99
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff8142d7e6)
Location: crypto/kpp.c:99
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff81460465)
Location: crypto/kpp.c:99
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff8147dea5)
Location: crypto/kpp.c:95
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff814ac1c5)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff814c6e75)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff81526125)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff815430c5)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff8154b765)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff815abf45)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff8165397b)
Location: crypto/kpp.c:107
Inline: True
Inline callers:
  - crypto/kpp.c:kpp_register_instance
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff8170d8bb)
Location: crypto/kpp.c:113
Inline: True
Inline callers:
  - crypto/kpp.c:kpp_register_instance
  - crypto/kpp.c:crypto_register_kpp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kpp_prepare_alg(struct kpp_alg *alg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (ffffffff81747e20)
Location: crypto/kpp.c:132
Inline: False
Direct callers:
  - crypto/kpp.c:kpp_register_instance
  - crypto/kpp.c:crypto_register_kpp
```
**Symbols:**

```
ffffffff81747e20-ffffffff81747e6a: kpp_prepare_alg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kpp_prepare_alg(struct kpp_alg *alg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kpp.c (ffffffff81789c90)
Location: crypto/kpp.c:132
Inline: False
Direct callers:
  - crypto/kpp.c:kpp_register_instance
  - crypto/kpp.c:crypto_register_kpp
```
**Symbols:**

```
ffffffff81789c90-ffffffff81789cda: kpp_prepare_alg (STB_LOCAL)
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
In crypto/kpp.c (ffff8000105c2528)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (c076f970)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (c00000000074ad1c)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffe000406f6c)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff814bf455)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff814afe75)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff814bb4e5)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
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
In crypto/kpp.c (ffffffff814d3fb5)
Location: crypto/kpp.c:90
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_register_kpp
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
