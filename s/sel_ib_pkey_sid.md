# Function: <code>sel_ib_pkey_sid</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff813b0580)
Location: security/selinux/ibpkey.c:189
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff813b0580-ffffffff813b073c: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff813d6620)
Location: security/selinux/ibpkey.c:189
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff813d6620-ffffffff813d67dc: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff81406c30)
Location: security/selinux/ibpkey.c:190
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff81406c30-ffffffff81406dec: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff814227a0)
Location: security/selinux/ibpkey.c:190
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff814227a0-ffffffff8142295c: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff81450430)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff81450430-ffffffff8145060d: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff8146a210)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff8146a210-ffffffff8146a3ed: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff814d19b0)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff814d19b0-ffffffff814d1a22: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff814eeec0)
Location: security/selinux/ibpkey.c:182
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff814eeec0-ffffffff814eef51: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff814f5a60)
Location: security/selinux/ibpkey.c:181
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff814f5a60-ffffffff814f5c73: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff81550460)
Location: security/selinux/ibpkey.c:181
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff81550460-ffffffff81550677: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff815e98e0)
Location: security/selinux/ibpkey.c:181
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff815e98e0-ffffffff815e9b27: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff81699250)
Location: security/selinux/ibpkey.c:181
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff81699250-ffffffff81699497: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff816d1710)
Location: security/selinux/ibpkey.c:181
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff816d1710-ffffffff816d1946: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff8170dd40)
Location: security/selinux/ibpkey.c:181
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff8170dd40-ffffffff8170dfa5: sel_ib_pkey_sid (STB_GLOBAL)
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
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffff800010558c00)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffff800010558c00-ffff800010558e8c: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (c070d668)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
c070d668-c070d888: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (c0000000006b6be0)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
c0000000006b6be0-c0000000006b6e74: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffe0003aff8c)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffe0003aff8c-ffffffe0003b0120: sel_ib_pkey_sid (STB_GLOBAL)
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
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff814627f0)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff814627f0-ffffffff814629cd: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff81453220)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff81453220-ffffffff814533fd: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff8145e890)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff8145e890-ffffffff8145ea6d: sel_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sel_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff81476070)
Location: security/selinux/ibpkey.c:180
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_pkey_access
```
**Symbols:**

```
ffffffff81476070-ffffffff8147627b: sel_ib_pkey_sid (STB_GLOBAL)
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
