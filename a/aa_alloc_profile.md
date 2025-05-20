# Function: <code>aa_alloc_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137fa20)
Location: security/apparmor/policy.c:234
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff8137fa20-ffffffff8137fb42: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b93e0)
Location: security/apparmor/policy.c:259
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff813b93e0-ffffffff813b9501: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d07a0)
Location: security/apparmor/policy.c:259
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff813d07a0-ffffffff813d08c1: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e3d80)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff813e3d80-ffffffff813e3e5d: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140ab60)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff8140ab60-ffffffff8140ac47: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143c420)
Location: security/apparmor/policy.c:259
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff8143c420-ffffffff8143c511: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81459290)
Location: security/apparmor/policy.c:259
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff81459290-ffffffff81459388: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81486a30)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff81486a30-ffffffff81486b23: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a08e0)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff814a08e0-ffffffff814a09d3: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fa990)
Location: security/apparmor/policy.c:258
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff814fa990-ffffffff814faab3: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81517710)
Location: security/apparmor/policy.c:258
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff81517710-ffffffff81517833: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151dfc0)
Location: security/apparmor/policy.c:258
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff8151dfc0-ffffffff8151e0e3: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157c0c0)
Location: security/apparmor/policy.c:258
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff8157c0c0-ffffffff8157c23f: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8161a7a0)
Location: security/apparmor/policy.c:293
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_unconfined
```
**Symbols:**

```
ffffffff8161a7a0-ffffffff8161a972: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816cd770)
Location: security/apparmor/policy.c:297
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff816cd770-ffffffff816cd965: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff817063a0)
Location: security/apparmor/policy.c:335
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff817063a0-ffffffff817065c1: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81743d00)
Location: security/apparmor/policy.c:337
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81743d00-ffffffff81743f45: aa_alloc_profile (STB_GLOBAL)
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
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010596660)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffff800010596660-ffff800010596754: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c0747764)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
c0747764-c074783c: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070c350)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
c00000000070c350-c00000000070c498: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e33fa)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffe0003e33fa-ffffffe0003e34c0: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81498ec0)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff81498ec0-ffffffff81498fb3: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814898e0)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff814898e0-ffffffff814899d3: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81494f60)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff81494f60-ffffffff81495053: aa_alloc_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_profile *aa_alloc_profile(const char *hname, struct aa_proxy *proxy, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814acf80)
Location: security/apparmor/policy.c:254
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff814acf80-ffffffff814ad073: aa_alloc_profile (STB_GLOBAL)
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
