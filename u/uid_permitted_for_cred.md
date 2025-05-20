# Function: <code>uid_permitted_for_cred</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffff81499220-ffffffff81499260: uid_permitted_for_cred (STB_LOCAL)
ffffffff81499366-ffffffff81499385: uid_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffff814b3140-ffffffff814b3180: uid_permitted_for_cred (STB_LOCAL)
ffffffff814b3286-ffffffff814b32a5: uid_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffff81512520-ffffffff815125a1: uid_permitted_for_cred (STB_LOCAL)
ffffffff81512726-ffffffff8151274a: uid_permitted_for_cred.cold (STB_LOCAL)
```
</details>
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
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffff8000105aad60)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffff8000105aad60-ffff8000105aadf0: uid_permitted_for_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c075a95c)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
c075a95c-c075a9e4: uid_permitted_for_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c0000000007288e0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
c0000000007288e0-c0000000007289ac: uid_permitted_for_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffe0003f39e6)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffe0003f39e6-ffffffe0003f3a66: uid_permitted_for_cred (STB_LOCAL)
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
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffff814ab720-ffffffff814ab760: uid_permitted_for_cred (STB_LOCAL)
ffffffff814ab866-ffffffff814ab885: uid_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffff8149c140-ffffffff8149c180: uid_permitted_for_cred (STB_LOCAL)
ffffffff8149c286-ffffffff8149c2a5: uid_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffff814a77c0-ffffffff814a7800: uid_permitted_for_cred (STB_LOCAL)
ffffffff814a7906-ffffffff814a7925: uid_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool uid_permitted_for_cred(const struct cred *old, kuid_t new_uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:100
Inline: False
```
**Symbols:**

```
ffffffff814c0150-ffffffff814c0190: uid_permitted_for_cred (STB_LOCAL)
ffffffff814c0296-ffffffff814c02b5: uid_permitted_for_cred.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
