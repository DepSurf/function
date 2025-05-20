# Function: <code>aa_dfa_unpack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81379080)
Location: security/apparmor/match.c:230
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff81379080-ffffffff813794f5: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813b1e20)
Location: security/apparmor/match.c:234
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff813b1e20-ffffffff813b2277: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813c8fe0)
Location: security/apparmor/match.c:234
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff813c8fe0-ffffffff813c9437: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813de670)
Location: security/apparmor/match.c:234
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff813de670-ffffffff813deb1f: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81405000)
Location: security/apparmor/match.c:234
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff81405000-ffffffff814054b5: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:285
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff81436cad-ffffffff81436cc0: aa_dfa_unpack.cold.5 (STB_LOCAL)
ffffffff814360f0-ffffffff814365bf: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:285
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff8145390d-ffffffff81453920: aa_dfa_unpack.cold.4 (STB_LOCAL)
ffffffff81452d10-ffffffff81453211: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:281
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff81481274-ffffffff81481287: aa_dfa_unpack.cold (STB_LOCAL)
ffffffff814806c0-ffffffff81480b76: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff8149af86-ffffffff8149afbf: aa_dfa_unpack.cold (STB_LOCAL)
ffffffff8149a3c0-ffffffff8149a87e: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f2e70)
Location: security/apparmor/match.c:306
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff814f2e70-ffffffff814f3112: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81510040)
Location: security/apparmor/match.c:306
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff81510040-ffffffff815102e2: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815168d0)
Location: security/apparmor/match.c:306
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff815168d0-ffffffff81516c96: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815748d0)
Location: security/apparmor/match.c:306
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff815748d0-ffffffff81574c96: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816123b0)
Location: security/apparmor/match.c:306
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_pdb
```
**Symbols:**

```
ffffffff816123b0-ffffffff81612642: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c5060)
Location: security/apparmor/match.c:306
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_pdb
```
**Symbols:**

```
ffffffff816c5060-ffffffff816c52f2: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fdaa0)
Location: security/apparmor/match.c:262
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:notify_set_filter
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
**Symbols:**

```
ffffffff816fdaa0-ffffffff816fdf00: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173b000)
Location: security/apparmor/match.c:262
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:notify_set_filter
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/lsm.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff8173b000-ffffffff8173b48c: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff800010590490)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffff800010590490-ffff8000105909bc: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c0741198)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
c0741198-c07416fc: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c000000000703ad0)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
c000000000703ad0-c000000000704198: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003ddf36)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffe0003ddf36-ffffffe0003de436: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff81493566-ffffffff8149359f: aa_dfa_unpack.cold (STB_LOCAL)
ffffffff814929a0-ffffffff81492e5e: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff81483f86-ffffffff81483fbf: aa_dfa_unpack.cold (STB_LOCAL)
ffffffff814833c0-ffffffff8148387e: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff8148f606-ffffffff8148f63f: aa_dfa_unpack.cold (STB_LOCAL)
ffffffff8148ea40-ffffffff8148eefe: aa_dfa_unpack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct aa_dfa *aa_dfa_unpack(void *blob, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/match.c (0)
Location: security/apparmor/match.c:296
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:unpack_dfa
```
**Symbols:**

```
ffffffff814a7516-ffffffff814a754f: aa_dfa_unpack.cold (STB_LOCAL)
ffffffff814a6950-ffffffff814a6e0e: aa_dfa_unpack (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
