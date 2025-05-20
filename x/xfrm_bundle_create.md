# Function: <code>xfrm_bundle_create</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b243d)
Location: net/xfrm/xfrm_policy.c:1653
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
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
In net/xfrm/xfrm_policy.c (ffffffff8181f421)
Location: net/xfrm/xfrm_policy.c:1657
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
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
In net/xfrm/xfrm_policy.c (ffffffff81850c81)
Location: net/xfrm/xfrm_policy.c:1685
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
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
In net/xfrm/xfrm_policy.c (ffffffff81875b9d)
Location: net/xfrm/xfrm_policy.c:1675
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
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
In net/xfrm/xfrm_policy.c (ffffffff818f6c91)
Location: net/xfrm/xfrm_policy.c:1545
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
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
In net/xfrm/xfrm_policy.c (ffffffff8194cd92)
Location: net/xfrm/xfrm_policy.c:1548
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197e640)
Location: net/xfrm/xfrm_policy.c:2541
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff8197e640-ffffffff8197eef9: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:2532
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff819e75a0-ffffffff819e7e4b: xfrm_bundle_create (STB_LOCAL)
ffffffff819ed7b5-ffffffff819ed7d3: xfrm_bundle_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1e590)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81a1e590-ffffffff81a1ee49: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b110f0)
Location: net/xfrm/xfrm_policy.c:2525
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81b110f0-ffffffff81b118eb: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1f990)
Location: net/xfrm/xfrm_policy.c:2535
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81b1f990-ffffffff81b201c4: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0d870)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81b0d870-ffffffff81b0e0a6: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd0430)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81bd0430-ffffffff81bd0caa: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d66980)
Location: net/xfrm/xfrm_policy.c:2532
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81d66980-ffffffff81d67298: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f31700)
Location: net/xfrm/xfrm_policy.c:2606
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81f31700-ffffffff81f31f9c: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f90cf0)
Location: net/xfrm/xfrm_policy.c:2608
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81f90cf0-ffffffff81f91591: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205ea60)
Location: net/xfrm/xfrm_policy.c:2628
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff8205ea60-ffffffff8205f2fd: xfrm_bundle_create (STB_LOCAL)
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
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdaa18)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffff800010cdaa18-ffff800010cdb238: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de48a0)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
c0de48a0-c0de5078: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dff950)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
c000000000dff950-c000000000e002e0: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082c652)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffe00082c652-ffffffe00082cc8e: xfrm_bundle_create (STB_LOCAL)
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
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bdc20)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff819bdc20-ffffffff819be4d9: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197aa10)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff8197aa10-ffffffff8197b2c9: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a286a0)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81a286a0-ffffffff81a28f59: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *xfrm_bundle_create(struct xfrm_policy *policy, struct xfrm_state **xfrm, struct xfrm_dst **bundle, int nx, const struct flowi *fl, struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a33c90)
Location: net/xfrm/xfrm_policy.c:2534
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81a33c90-ffffffff81a345b8: xfrm_bundle_create (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
