# Function: <code>aa_label_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138a1d0)
Location: security/apparmor/label.c:383
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff8138a1d0-ffffffff8138a266: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c4eb0)
Location: security/apparmor/label.c:383
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff813c4eb0-ffffffff813c4f46: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dc500)
Location: security/apparmor/label.c:399
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff813dc500-ffffffff813dc596: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ed163)
Location: security/apparmor/label.c:405
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff813ed0c0-ffffffff813ed107: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414b6f)
Location: security/apparmor/label.c:405
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff81414ad0-ffffffff81414b17: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446f6f)
Location: security/apparmor/label.c:405
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff81446ed0-ffffffff81446f16: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463e9f)
Location: security/apparmor/label.c:405
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff81463e00-ffffffff81463e47: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149114d)
Location: security/apparmor/label.c:401
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff814910b0-ffffffff814910fa: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aaffd)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff814aaf60-ffffffff814aafaa: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815099fe)
Location: security/apparmor/label.c:396
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff81509960-ffffffff815099a8: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152686e)
Location: security/apparmor/label.c:396
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff815267d0-ffffffff81526818: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152c1fe)
Location: security/apparmor/label.c:396
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff8152c160-ffffffff8152c1a8: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158a5ec)
Location: security/apparmor/label.c:396
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff8158a540-ffffffff8158a588: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162ba58)
Location: security/apparmor/label.c:399
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff8162b990-ffffffff8162b9e0: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e0337)
Location: security/apparmor/label.c:399
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff816e0270-ffffffff816e02c0: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81719968)
Location: security/apparmor/label.c:399
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff817198a0-ffffffff817198f0: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81758408)
Location: security/apparmor/label.c:405
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff81758340-ffffffff81758390: aa_label_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1fac)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffff8000105a1ef0-ffff8000105a1f54: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752648)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
c075258c-c07525e4: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071cf3c)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
c00000000071ce20-c00000000071cebc: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003eca0c)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffe0003ec956-ffffffe0003ec9b4: aa_label_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a35dd)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff814a3540-ffffffff814a358a: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81493ffd)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff81493f60-ffffffff81493faa: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f67d)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff8149f5e0-ffffffff8149f62a: aa_label_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool aa_label_init(struct aa_label *label, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7cad)
Location: security/apparmor/label.c:395
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
**Symbols:**

```
ffffffff814b7c10-ffffffff814b7c5a: aa_label_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
