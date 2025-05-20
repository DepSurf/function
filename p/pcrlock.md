# Function: <code>pcrlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81336a30)
Location: security/keys/trusted.c:378
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81336a30-ffffffff81336ab3: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8136bf80)
Location: security/keys/trusted.c:378
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff8136bf80-ffffffff8136c003: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813827a0)
Location: security/keys/trusted.c:378
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff813827a0-ffffffff81382823: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81396e20)
Location: security/keys/trusted.c:378
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81396e20-ffffffff81396ea2: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813bc600)
Location: security/keys/trusted.c:378
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff813bc600-ffffffff813bc682: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813ed440)
Location: security/keys/trusted.c:377
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff813ed440-ffffffff813ed4bc: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81408c80)
Location: security/keys/trusted.c:380
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81408c80-ffffffff81408cfc: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81435780)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81435780-ffffffff814357c8: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8144f520)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff8144f520-ffffffff8144f568: pcrlock (STB_LOCAL)
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a2c2f)
Location: security/keys/trusted-keys/trusted_tpm1.c:387
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c05ff)
Location: security/keys/trusted-keys/trusted_tpm1.c:387
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c60f2)
Location: security/keys/trusted-keys/trusted_tpm1.c:380
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151eb20)
Location: security/keys/trusted-keys/trusted_tpm1.c:380
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b214f)
Location: security/keys/trusted-keys/trusted_tpm1.c:380
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165ccff)
Location: security/keys/trusted-keys/trusted_tpm1.c:380
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8169561f)
Location: security/keys/trusted-keys/trusted_tpm1.c:380
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
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
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d1c4f)
Location: security/keys/trusted-keys/trusted_tpm1.c:380
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
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
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053a3c0)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffff80001053a3c0-ffff80001053a420: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f0c4c)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
c06f0c4c-c06f0c9c: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c000000000689040)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
c000000000689040-c0000000006890c8: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe0003985ba)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffe0003985ba-ffffffe00039860a: pcrlock (STB_LOCAL)
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
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81447b00)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81447b00-ffffffff81447b48: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81438550)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81438550-ffffffff81438598: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81443ba0)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81443ba0-ffffffff81443be8: pcrlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pcrlock(const int pcrnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8145aed0)
Location: security/keys/trusted.c:387
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff8145aed0-ffffffff8145af18: pcrlock (STB_LOCAL)
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
