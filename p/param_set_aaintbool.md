# Function: <code>param_set_aaintbool</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145d780)
Location: security/apparmor/lsm.c:1472
Inline: False
```
**Symbols:**

```
ffffffff8145d780-ffffffff8145d81b: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148ada0)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffffffff8148ada0-ffffffff8148ae3b: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a4c60)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffffffff814a4c60-ffffffff814a4cfb: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814ffb70)
Location: security/apparmor/lsm.c:1574
Inline: False
```
**Symbols:**

```
ffffffff814ffb70-ffffffff814ffc0a: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8151cd60)
Location: security/apparmor/lsm.c:1574
Inline: False
```
**Symbols:**

```
ffffffff8151cd60-ffffffff8151cdfa: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81523570)
Location: security/apparmor/lsm.c:1584
Inline: False
```
**Symbols:**

```
ffffffff81523570-ffffffff8152360a: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1584
Inline: False
```
**Symbols:**

```
ffffffff81581b90-ffffffff81581c3d: param_set_aaintbool (STB_LOCAL)
ffffffff81cd6608-ffffffff81cd6623: param_set_aaintbool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1824
Inline: False
```
**Symbols:**

```
ffffffff81621060-ffffffff81621143: param_set_aaintbool (STB_LOCAL)
ffffffff81e89537-ffffffff81e89552: param_set_aaintbool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1888
Inline: False
```
**Symbols:**

```
ffffffff816d4920-ffffffff816d4a03: param_set_aaintbool (STB_LOCAL)
ffffffff82074c47-ffffffff82074c62: param_set_aaintbool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:2044
Inline: False
```
**Symbols:**

```
ffffffff8170d8b0-ffffffff8170d993: param_set_aaintbool (STB_LOCAL)
ffffffff820f484c-ffffffff820f4867: param_set_aaintbool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:2065
Inline: False
```
**Symbols:**

```
ffffffff8174b740-ffffffff8174b823: param_set_aaintbool (STB_LOCAL)
ffffffff821d1ca6-ffffffff821d1cc1: param_set_aaintbool.cold (STB_LOCAL)
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
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059ab90)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffff80001059ab90-ffff80001059ac4c: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074bcc4)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
c074bcc4-c074bd94: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c000000000712520)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
c000000000712520-c00000000071261c: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7138)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffffffe0003e7138-ffffffe0003e71ae: param_set_aaintbool (STB_LOCAL)
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
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149d240)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffffffff8149d240-ffffffff8149d2db: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148dc60)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffffffff8148dc60-ffffffff8148dcfb: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814992e0)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffffffff814992e0-ffffffff8149937b: param_set_aaintbool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int param_set_aaintbool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b1460)
Location: security/apparmor/lsm.c:1468
Inline: False
```
**Symbols:**

```
ffffffff814b1460-ffffffff814b14fb: param_set_aaintbool (STB_LOCAL)
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
