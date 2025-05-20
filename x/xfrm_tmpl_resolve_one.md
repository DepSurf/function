# Function: <code>xfrm_tmpl_resolve_one</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b17b9)
Location: net/xfrm/xfrm_policy.c:1414
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff8181e709)
Location: net/xfrm/xfrm_policy.c:1418
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff8184ff89)
Location: net/xfrm/xfrm_policy.c:1446
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff81873d53)
Location: net/xfrm/xfrm_policy.c:1440
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff818f4ec3)
Location: net/xfrm/xfrm_policy.c:1363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff8194be9f)
Location: net/xfrm/xfrm_policy.c:1363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff8197e141)
Location: net/xfrm/xfrm_policy.c:2355
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff819e7efe)
Location: net/xfrm/xfrm_policy.c:2361
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff81a1eefe)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0f870)
Location: net/xfrm/xfrm_policy.c:2354
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff81b0f870-ffffffff81b0fb8b: xfrm_tmpl_resolve_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1dd50)
Location: net/xfrm/xfrm_policy.c:2364
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff81b1dd50-ffffffff81b1e07a: xfrm_tmpl_resolve_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0b6f0)
Location: net/xfrm/xfrm_policy.c:2363
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff81b0b6f0-ffffffff81b0ba1d: xfrm_tmpl_resolve_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bce640)
Location: net/xfrm/xfrm_policy.c:2363
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff81bce640-ffffffff81bce9da: xfrm_tmpl_resolve_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d64680)
Location: net/xfrm/xfrm_policy.c:2363
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff81d64680-ffffffff81d64a57: xfrm_tmpl_resolve_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2f3a0)
Location: net/xfrm/xfrm_policy.c:2437
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff81f2f3a0-ffffffff81f2f777: xfrm_tmpl_resolve_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8fe30)
Location: net/xfrm/xfrm_policy.c:2439
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff81f8fe30-ffffffff81f90206: xfrm_tmpl_resolve_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm_tmpl_resolve_one(struct xfrm_policy *policy, const struct flowi *fl, struct xfrm_state **xfrm, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205db90)
Location: net/xfrm/xfrm_policy.c:2459
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
**Symbols:**

```
ffffffff8205db90-ffffffff8205df66: xfrm_tmpl_resolve_one (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffff800010cda300)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (c0de5110)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
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
In net/xfrm/xfrm_policy.c (c000000000dfbfb0)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffe00082a72a)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff819be58e)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff8197b37e)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff81a2900e)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
In net/xfrm/xfrm_policy.c (ffffffff81a34668)
Location: net/xfrm/xfrm_policy.c:2363
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
