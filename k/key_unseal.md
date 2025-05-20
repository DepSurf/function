# Function: <code>key_unseal</code>

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
In security/keys/trusted.c (ffffffff813386de)
Location: security/keys/trusted.c:688
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff8136dcce)
Location: security/keys/trusted.c:688
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff813844ee)
Location: security/keys/trusted.c:688
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff81398ac3)
Location: security/keys/trusted.c:688
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff813be2d3)
Location: security/keys/trusted.c:688
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff813eef6c)
Location: security/keys/trusted.c:687
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff8140a1dd)
Location: security/keys/trusted.c:691
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff814372d5)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff81451075)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int key_unseal(struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:682
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
```
**Symbols:**

```
ffffffff814a2360-ffffffff814a2436: key_unseal (STB_LOCAL)
ffffffff814a30ed-ffffffff814a3100: key_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int key_unseal(struct trusted_key_payload *p, struct trusted_key_options *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:692
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
```
**Symbols:**

```
ffffffff814bfd30-ffffffff814bfe06: key_unseal (STB_LOCAL)
ffffffff81befd36-ffffffff81befd49: key_unseal.cold (STB_LOCAL)
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c600e)
Location: security/keys/trusted-keys/trusted_tpm1.c:687
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151ea2e)
Location: security/keys/trusted-keys/trusted_tpm1.c:687
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b208b)
Location: security/keys/trusted-keys/trusted_tpm1.c:687
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165cc3b)
Location: security/keys/trusted-keys/trusted_tpm1.c:687
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8169555b)
Location: security/keys/trusted-keys/trusted_tpm1.c:687
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d1b8b)
Location: security/keys/trusted-keys/trusted_tpm1.c:687
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
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
In security/keys/trusted.c (ffff80001053c24c)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (c06f224c)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (c00000000068b774)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffe000399f16)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff81449655)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff8143a0a5)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff814456f5)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
In security/keys/trusted.c (ffffffff8145ca25)
Location: security/keys/trusted.c:696
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_instantiate
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
