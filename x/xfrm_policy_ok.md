# Function: <code>xfrm_policy_ok</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b645e)
Location: net/xfrm/xfrm_policy.c:2412
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff81823459)
Location: net/xfrm/xfrm_policy.c:2416
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff81854da9)
Location: net/xfrm/xfrm_policy.c:2444
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff81878930)
Location: net/xfrm/xfrm_policy.c:2390
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff818f9282)
Location: net/xfrm/xfrm_policy.c:2332
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff8194fcd2)
Location: net/xfrm/xfrm_policy.c:2342
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff81983352)
Location: net/xfrm/xfrm_policy.c:3244
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff819ecf5c)
Location: net/xfrm/xfrm_policy.c:3243
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff81a23f6c)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0f380)
Location: net/xfrm/xfrm_policy.c:3235
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81b0f380-ffffffff81b0f556: xfrm_policy_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1d670)
Location: net/xfrm/xfrm_policy.c:3256
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81b1d670-ffffffff81b1d846: xfrm_policy_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0afb0)
Location: net/xfrm/xfrm_policy.c:3255
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81b0afb0-ffffffff81b0b186: xfrm_policy_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3260
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81bcde20-ffffffff81bce05f: xfrm_policy_ok (STB_LOCAL)
ffffffff81d3ed59-ffffffff81d3ed90: xfrm_policy_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3263
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81d63f10-ffffffff81d64151: xfrm_policy_ok (STB_LOCAL)
ffffffff81f0b6a2-ffffffff81f0b6d3: xfrm_policy_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3337
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81f2ec80-ffffffff81f2eec1: xfrm_policy_ok (STB_LOCAL)
ffffffff820b2ee0-ffffffff820b2f11: xfrm_policy_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3340
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81f8f560-ffffffff81f8f7f6: xfrm_policy_ok (STB_LOCAL)
ffffffff821340de-ffffffff82134115: xfrm_policy_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_ok(const struct xfrm_tmpl *tmpl, const struct sec_path *sp, int start, short unsigned int family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3362
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff8205d2c0-ffffffff8205d556: xfrm_policy_ok (STB_LOCAL)
ffffffff82215ce4-ffffffff82215d1b: xfrm_policy_ok.cold (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffff800010ce11c0)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (c0dea520)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (c000000000e03748)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffe00082fd2e)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff819c35fc)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff819803ec)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff81a2e07c)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
In net/xfrm/xfrm_policy.c (ffffffff81a3986f)
Location: net/xfrm/xfrm_policy.c:3245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 if_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
