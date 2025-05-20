# Function: <code>sel_ib_pkey_sid_slow</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff813b05fd)
Location: security/selinux/ibpkey.c:140
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff813d669d)
Location: security/selinux/ibpkey.c:140
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff81406cae)
Location: security/selinux/ibpkey.c:140
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff8142281e)
Location: security/selinux/ibpkey.c:140
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff814504bf)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff8146a29f)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sel_ib_pkey_sid_slow(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff814d1800)
Location: security/selinux/ibpkey.c:130
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff814d1800-ffffffff814d19a6: sel_ib_pkey_sid_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sel_ib_pkey_sid_slow(u64 subnet_prefix, u16 pkey_num, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ibpkey.c (ffffffff814eed10)
Location: security/selinux/ibpkey.c:130
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff814eed10-ffffffff814eeebc: sel_ib_pkey_sid_slow (STB_LOCAL)
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
In security/selinux/ibpkey.c (ffffffff814f5afe)
Location: security/selinux/ibpkey.c:129
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff81550502)
Location: security/selinux/ibpkey.c:129
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff815e9998)
Location: security/selinux/ibpkey.c:129
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff81699308)
Location: security/selinux/ibpkey.c:129
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff816d17cb)
Location: security/selinux/ibpkey.c:129
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff8170ddfb)
Location: security/selinux/ibpkey.c:129
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffff800010558cb4)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (c070d710)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (c0000000006b6cd0)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffe0003b001a)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff8146287f)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff814532af)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff8145e91f)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
In security/selinux/ibpkey.c (ffffffff8147610e)
Location: security/selinux/ibpkey.c:130
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
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
</ul>
