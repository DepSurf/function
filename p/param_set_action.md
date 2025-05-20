# Function: <code>param_set_action</code>

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
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:184
Inline: False
```
**Symbols:**

```
ffffffff81099250-ffffffff81099323: param_set_action (STB_LOCAL)
ffffffff81099eaf-ffffffff81099f15: param_set_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:184
Inline: False
```
**Symbols:**

```
ffffffff8109e8e0-ffffffff8109e9b7: param_set_action (STB_LOCAL)
ffffffff8109f50f-ffffffff8109f586: param_set_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:198
Inline: False
```
**Symbols:**

```
ffffffff8109a4c0-ffffffff8109a56f: param_set_action (STB_LOCAL)
ffffffff81bda5f7-ffffffff81bda693: param_set_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:201
Inline: False
```
**Symbols:**

```
ffffffff8109ac80-ffffffff8109ad2f: param_set_action (STB_LOCAL)
ffffffff81bcc71f-ffffffff81bcc7bb: param_set_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:201
Inline: False
```
**Symbols:**

```
ffffffff810aaf10-ffffffff810ab008: param_set_action (STB_LOCAL)
ffffffff81ca2b37-ffffffff81ca2bca: param_set_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:201
Inline: False
```
**Symbols:**

```
ffffffff810c0980-ffffffff810c0a49: param_set_action (STB_LOCAL)
ffffffff81e523ad-ffffffff81e5247e: param_set_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dc9d0)
Location: arch/x86/platform/uv/uv_nmi.c:201
Inline: False
```
**Symbols:**

```
ffffffff810dc9d0-ffffffff810dcbea: param_set_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e7fb0)
Location: arch/x86/platform/uv/uv_nmi.c:201
Inline: False
```
**Symbols:**

```
ffffffff810e7fb0-ffffffff810e81ca: param_set_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f0400)
Location: arch/x86/platform/uv/uv_nmi.c:217
Inline: True
```
**Symbols:**

```
ffffffff810f0400-ffffffff810f0507: param_set_action (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int param_set_action(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:184
Inline: False
```
**Symbols:**

```
ffffffff8109a720-ffffffff8109a7f3: param_set_action (STB_LOCAL)
ffffffff8109b37f-ffffffff8109b3e5: param_set_action.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
