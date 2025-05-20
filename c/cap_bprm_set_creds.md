# Function: <code>cap_bprm_set_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8133ac40)
Location: security/commoncap.c:491
Inline: False
```
**Symbols:**

```
ffffffff8133ac40-ffffffff8133b234: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813701d0)
Location: security/commoncap.c:497
Inline: False
```
**Symbols:**

```
ffffffff813701d0-ffffffff813707b6: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813869e0)
Location: security/commoncap.c:492
Inline: False
```
**Symbols:**

```
ffffffff813869e0-ffffffff81386fc6: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139b6b0)
Location: security/commoncap.c:712
Inline: False
```
**Symbols:**

```
ffffffff8139b6b0-ffffffff8139bc7d: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813c0cc0)
Location: security/commoncap.c:813
Inline: False
```
**Symbols:**

```
ffffffff813c0cc0-ffffffff813c1355: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:815
Inline: False
```
**Symbols:**

```
ffffffff813f2377-ffffffff813f23b9: cap_bprm_set_creds.cold.8 (STB_LOCAL)
ffffffff813f1c30-ffffffff813f2273: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:810
Inline: False
```
**Symbols:**

```
ffffffff8140d637-ffffffff8140d679: cap_bprm_set_creds.cold.8 (STB_LOCAL)
ffffffff8140cf00-ffffffff8140d538: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffffffff8143a7c0-ffffffff8143a840: cap_bprm_set_creds.cold (STB_LOCAL)
ffffffff8143a0b0-ffffffff8143a6ab: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffffffff81454637-ffffffff81454672: cap_bprm_set_creds.cold (STB_LOCAL)
ffffffff81453f20-ffffffff81454538: cap_bprm_set_creds (STB_GLOBAL)
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
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053f060)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffff80001053f060-ffff80001053f644: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f502c)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
c06f502c-c06f5784: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c00000000068f9d0)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
c00000000068f9d0-c0000000006901b4: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039c620)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffffffe00039c620-ffffffe00039cb32: cap_bprm_set_creds (STB_GLOBAL)
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
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffffffff8144cc17-ffffffff8144cc52: cap_bprm_set_creds.cold (STB_LOCAL)
ffffffff8144c500-ffffffff8144cb18: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffffffff8143d667-ffffffff8143d6a2: cap_bprm_set_creds.cold (STB_LOCAL)
ffffffff8143cf50-ffffffff8143d568: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffffffff81448cb7-ffffffff81448cf2: cap_bprm_set_creds.cold (STB_LOCAL)
ffffffff814485a0-ffffffff81448bb8: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cap_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:807
Inline: False
```
**Symbols:**

```
ffffffff81460087-ffffffff814600c2: cap_bprm_set_creds.cold (STB_LOCAL)
ffffffff8145f970-ffffffff8145ff88: cap_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
