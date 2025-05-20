# Function: <code>ima_load_data</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:508
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff8146f045-ffffffff8146f071: ima_load_data.cold.3 (STB_LOCAL)
ffffffff8146efb0-ffffffff8146f02f: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:568
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff8149caf1-ffffffff8149cb33: ima_load_data.cold (STB_LOCAL)
ffffffff8149c9e0-ffffffff8149ca54: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff814b6e2f-ffffffff814b6e71: ima_load_data.cold (STB_LOCAL)
ffffffff814b6b60-ffffffff814b6bd4: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:687
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff81516632-ffffffff81516674: ima_load_data.cold (STB_LOCAL)
ffffffff81516350-ffffffff815163ba: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:742
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff81bf1b9f-ffffffff81bf1be1: ima_load_data.cold (STB_LOCAL)
ffffffff81533490-ffffffff815334ff: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:755
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff81be3bc1-ffffffff81be3c03: ima_load_data.cold (STB_LOCAL)
ffffffff8153b9e0-ffffffff8153ba4f: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:772
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff81cd6e16-ffffffff81cd6e58: ima_load_data.cold (STB_LOCAL)
ffffffff8159a470-ffffffff8159a4df: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:795
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff81e8a046-ffffffff81e8a078: ima_load_data.cold (STB_LOCAL)
ffffffff8163f1a0-ffffffff8163f21e: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f6eb0)
Location: security/integrity/ima/ima_main.c:805
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff816f6eb0-ffffffff816f6f49: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81731130)
Location: security/integrity/ima/ima_main.c:824
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff81731130-ffffffff817311c8: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81771b90)
Location: security/integrity/ima/ima_main.c:838
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff81771b90-ffffffff81771c28: ima_load_data (STB_GLOBAL)
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
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffff8000105aee58)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffff8000105aee58-ffff8000105aef1c: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c075e56c)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
c075e56c-c075e61c: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c00000000072dff0)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
c00000000072dff0-c00000000072e128: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffe0003f6e02)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffe0003f6e02-ffffffe0003f6eb6: ima_load_data (STB_GLOBAL)
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
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff814af40f-ffffffff814af451: ima_load_data.cold (STB_LOCAL)
ffffffff814af140-ffffffff814af1b4: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff8149fe2f-ffffffff8149fe71: ima_load_data.cold (STB_LOCAL)
ffffffff8149fb60-ffffffff8149fbd4: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff814ab49f-ffffffff814ab4e1: ima_load_data.cold (STB_LOCAL)
ffffffff814ab1e0-ffffffff814ab244: ima_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:588
Inline: False
Direct callers:
  - security/security.c:security_kernel_load_data
```
**Symbols:**

```
ffffffff814c3eef-ffffffff814c3f31: ima_load_data.cold (STB_LOCAL)
ffffffff814c3c20-ffffffff814c3c94: ima_load_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool contents</code>
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
