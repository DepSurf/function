# Function: <code>init_digests</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff828e6a56)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (ffffffff828ef50f)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff82d046da)
Location: security/keys/trusted-keys/trusted_tpm1.c:1205
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
```
**Symbols:**

```
ffffffff82d046da-ffffffff82d04746: init_digests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff82ff1aa7)
Location: security/keys/trusted-keys/trusted_tpm1.c:1219
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
```
**Symbols:**

```
ffffffff82ff1aa7-ffffffff82ff1b13: init_digests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff831fc42e)
Location: security/keys/trusted-keys/trusted_tpm1.c:1015
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
**Symbols:**

```
ffffffff831fc42e-ffffffff831fc49a: init_digests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff832e3480)
Location: security/keys/trusted-keys/trusted_tpm1.c:1015
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
**Symbols:**

```
ffffffff832e3480-ffffffff832e34ec: init_digests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8349988a)
Location: security/keys/trusted-keys/trusted_tpm1.c:1015
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
**Symbols:**

```
ffffffff8349988a-ffffffff834998ff: init_digests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff83ecf950)
Location: security/keys/trusted-keys/trusted_tpm1.c:1015
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
**Symbols:**

```
ffffffff83ecf950-ffffffff83ecf9fd: init_digests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff836f4a10)
Location: security/keys/trusted-keys/trusted_tpm1.c:1015
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
**Symbols:**

```
ffffffff836f4a10-ffffffff836f4abd: init_digests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_digests();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff83927c10)
Location: security/keys/trusted-keys/trusted_tpm1.c:1015
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
**Symbols:**

```
ffffffff83927c10-ffffffff83927cbd: init_digests (STB_LOCAL)
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
In security/keys/trusted.c (ffff8000114691e8)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (c1541d1c)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (c0000000013972c8)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (ffffffe000024428)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (ffffffff828d83c3)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (ffffffff828d0adf)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (ffffffff828eb143)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
In security/keys/trusted.c (ffffffff828f0559)
Location: security/keys/trusted.c:1229
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
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
