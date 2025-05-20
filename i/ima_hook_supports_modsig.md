# Function: <code>ima_hook_supports_modsig</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814bc3c0)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff814bc3c0-ffffffff814bc3de: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff8151c8c0)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff8151c8c0-ffffffff8151c8de: ima_hook_supports_modsig (STB_GLOBAL)
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
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffff8000105b4de0)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffff8000105b4de0-ffff8000105b4e1c: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (c076407c)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
c076407c-c07640b4: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (c000000000737df0)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
c000000000737df0-c000000000737e28: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffe0003fbe6e)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffe0003fbe6e-ffffffe0003fbe9e: ima_hook_supports_modsig (STB_GLOBAL)
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
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814b49a0)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff814b49a0-ffffffff814b49be: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814a53c0)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff814a53c0-ffffffff814a53de: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814b0a30)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff814b0a30-ffffffff814b0a4e: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ima_hook_supports_modsig(enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814c94b0)
Location: security/integrity/ima/ima_modsig.c:43
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff814c94b0-ffffffff814c94ce: ima_hook_supports_modsig (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
