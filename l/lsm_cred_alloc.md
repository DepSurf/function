# Function: <code>lsm_cred_alloc</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lsm_cred_alloc(struct cred *cred, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f6d2)
Location: security/security.c:325
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:lsm_early_cred
```
**Symbols:**

```
ffffffff8139d980-ffffffff8139d9bd: lsm_cred_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lsm_cred_alloc(struct cred *cred, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c525d)
Location: security/security.c:340
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:lsm_early_cred
```
**Symbols:**

```
ffffffff813c3270-ffffffff813c32ae: lsm_cred_alloc (STB_GLOBAL)
```
</details>
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
In security/security.c (ffffffff81410905)
Location: security/security.c:492
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff8143e0a5)
Location: security/security.c:491
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff81457b45)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int lsm_cred_alloc(struct cred *cred, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaa05)
Location: security/security.c:578
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
Direct callers:
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff814a9030-ffffffff814a9076: lsm_cred_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int lsm_cred_alloc(struct cred *cred, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c800e)
Location: security/security.c:580
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
Direct callers:
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff814c6630-ffffffff814c6676: lsm_cred_alloc (STB_LOCAL)
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
In security/security.c (ffffffff814ce64e)
Location: security/security.c:583
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff8152730e)
Location: security/security.c:583
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff815bc039)
Location: security/security.c:611
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff81667f39)
Location: security/security.c:660
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff816a0559)
Location: security/security.c:668
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff816dcf69)
Location: security/security.c:673
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffff800010543840)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (c06f979c)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (c000000000697a8c)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffe00039fce4)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff81450125)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff81440b75)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff8144c1c5)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff81463595)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_prepare_creds
  - security/security.c:security_cred_alloc_blank
  - security/security.c:ordered_lsm_init
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
