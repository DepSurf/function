# Function: <code>format_mk_user_description</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c2c4)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81391ca4)
Location: fs/crypto/keyring.c:190
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3051)
Location: fs/crypto/keyring.c:190
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff813aa291)
Location: fs/crypto/keyring.c:190
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff813f9ae1)
Location: fs/crypto/keyring.c:190
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff8146ca68)
Location: fs/crypto/keyring.c:190
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff814fde58)
Location: fs/crypto/keyring.c:176
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff81535448)
Location: fs/crypto/keyring.c:178
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff8156a418)
Location: fs/crypto/keyring.c:190
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffff80001040ce54)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void format_mk_user_description(char *description, const u8 *mk_identifier);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05d9d40)
Location: fs/crypto/keyring.c:186
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
```
**Symbols:**

```
c05d9d40-c05d9d90: format_mk_user_description (STB_LOCAL)
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
In fs/crypto/keyring.c (c00000000051a208)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffe0002b6656)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff813448a4)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff81335584)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff81342374)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
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
In fs/crypto/keyring.c (ffffffff81355674)
Location: fs/crypto/keyring.c:186
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:find_master_key_user
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
