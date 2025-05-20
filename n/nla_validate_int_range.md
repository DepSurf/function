# Function: <code>nla_validate_int_range</code>

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
In lib/nlattr.c (ffffffff81506500)
Location: lib/nlattr.c:98
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff81534332)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff81555176)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nla_validate_int_range(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815deb80)
Location: lib/nlattr.c:275
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815deb80-ffffffff815ded05: nla_validate_int_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nla_validate_int_range(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack, unsigned int validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:302
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815fc220-ffffffff815fc470: nla_validate_int_range (STB_LOCAL)
ffffffff81bf45f6-ffffffff81bf461a: nla_validate_int_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nla_validate_int_range(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack, unsigned int validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:302
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815dee70-ffffffff815df108: nla_validate_int_range (STB_LOCAL)
ffffffff81be64ea-ffffffff81be6510: nla_validate_int_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nla_validate_int_range(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack, unsigned int validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:302
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff8164a9f0-ffffffff8164ac88: nla_validate_int_range (STB_LOCAL)
ffffffff81cddd5f-ffffffff81cddd85: nla_validate_int_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nla_validate_int_range(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack, unsigned int validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:302
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff81761380-ffffffff8176164a: nla_validate_int_range (STB_LOCAL)
ffffffff81ea40ce-ffffffff81ea40f4: nla_validate_int_range.cold (STB_LOCAL)
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
In lib/nlattr.c (ffffffff81890718)
Location: lib/nlattr.c:313
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff818d2ba2)
Location: lib/nlattr.c:313
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff81924b57)
Location: lib/nlattr.c:325
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffff800010661558)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (c080a674)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (c0000000008154d0)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffe00048dfe8)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff8154d756)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff8153da36)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff81549496)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
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
In lib/nlattr.c (ffffffff815632e6)
Location: lib/nlattr.c:99
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int validate</code>
</li>
</ul>
</details>
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
</ul>
