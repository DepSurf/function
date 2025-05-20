# Function: <code>is_audit_feature_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81121dc0)
Location: kernel/audit.c:722
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81121dc0-ffffffff81121dda: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129d00)
Location: kernel/audit.c:719
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81129d00-ffffffff81129d1a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133a20)
Location: kernel/audit.c:859
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81133a20-ffffffff81133a3a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134f00)
Location: kernel/audit.c:1035
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81134f00-ffffffff81134f1a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141c50)
Location: kernel/audit.c:1035
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81141c50-ffffffff81141c6a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150600)
Location: kernel/audit.c:1078
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81150600-ffffffff8115061a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d2b0)
Location: kernel/audit.c:1074
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8115d2b0-ffffffff8115d2ca: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b4b8)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff811699f0-ffffffff81169a0a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81177398)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81175890-ffffffff811758aa: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118a101)
Location: kernel/audit.c:1096
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81187ff0-ffffffff8118800a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187411)
Location: kernel/audit.c:1100
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81185380-ffffffff8118539a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188349)
Location: kernel/audit.c:1100
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81186380-ffffffff8118639a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b0869)
Location: kernel/audit.c:1122
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff811ae770-ffffffff811ae78a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e2a4a)
Location: kernel/audit.c:1105
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff811e06e0-ffffffff811e0702: is_audit_feature_set (STB_GLOBAL)
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
In kernel/audit.c (ffffffff8122892a)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8123ef2a)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff81258d9b)
Location: kernel/audit.c:1114
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ec344)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffff8000101ea6e8-ffff8000101ea720: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042bf6c)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
c042a404-c042a434: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025dd18)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
c00000000025b9b0-c00000000025b9e0: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe000160a6e)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffe00015f0e4-ffffffe00015f116: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116f9b8)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116deb0-ffffffff8116deca: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81162b58)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81161050-ffffffff8116106a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d788)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116bc80-ffffffff8116bc9a: is_audit_feature_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int is_audit_feature_set(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117af78)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81179440-ffffffff8117945a: is_audit_feature_set (STB_GLOBAL)
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
