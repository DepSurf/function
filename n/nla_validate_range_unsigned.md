# Function: <code>nla_validate_range_unsigned</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fc2b0)
Location: lib/nlattr.c:162
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
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
In lib/nlattr.c (ffffffff815def05)
Location: lib/nlattr.c:162
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
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
In lib/nlattr.c (ffffffff8164aa85)
Location: lib/nlattr.c:162
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
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
In lib/nlattr.c (ffffffff817613d9)
Location: lib/nlattr.c:162
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nla_validate_range_unsigned(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack, unsigned int validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188fec0)
Location: lib/nlattr.c:165
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff8188fec0-ffffffff818900f7: nla_validate_range_unsigned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nla_validate_range_unsigned(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack, unsigned int validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d2330)
Location: lib/nlattr.c:165
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff818d2330-ffffffff818d2559: nla_validate_range_unsigned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nla_validate_range_unsigned(const struct nla_policy *pt, const struct nlattr *nla, struct netlink_ext_ack *extack, unsigned int validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81924300)
Location: lib/nlattr.c:170
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff81924300-ffffffff8192453b: nla_validate_range_unsigned (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
