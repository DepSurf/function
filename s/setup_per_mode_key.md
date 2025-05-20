# Function: <code>setup_per_mode_key</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff8134d7a0-ffffffff8134d8c7: setup_per_mode_key (STB_LOCAL)
ffffffff8134e051-ffffffff8134e05d: setup_per_mode_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040ea20)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffff80001040ea20-ffff80001040eb84: setup_per_mode_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db518)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
c05db518-c05db698: setup_per_mode_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051bfa0)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
c00000000051bfa0-c00000000051c1a4: setup_per_mode_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b791c)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffe0002b791c-ffffffe0002b7a04: setup_per_mode_key (STB_LOCAL)
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
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff81345d80-ffffffff81345ea7: setup_per_mode_key (STB_LOCAL)
ffffffff81346631-ffffffff8134663d: setup_per_mode_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff81336a60-ffffffff81336b87: setup_per_mode_key (STB_LOCAL)
ffffffff81337311-ffffffff8133731d: setup_per_mode_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff81343850-ffffffff81343977: setup_per_mode_key (STB_LOCAL)
ffffffff81344101-ffffffff8134410d: setup_per_mode_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:208
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff81356b30-ffffffff81356c57: setup_per_mode_key (STB_LOCAL)
ffffffff813573df-ffffffff813573eb: setup_per_mode_key.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
