# Function: <code>warn_bad_vsyscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810046d0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:69
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810046d0-ffffffff81004781: warn_bad_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810047e0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:69
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810047e0-ffffffff81004891: warn_bad_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004860)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:69
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81004860-ffffffff81004911: warn_bad_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810046f0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:71
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810046f0-ffffffff8100478a: warn_bad_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004960)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81004960-ffffffff810049fa: warn_bad_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:69
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810050e0-ffffffff81005128: warn_bad_vsyscall (STB_LOCAL)
ffffffff810055f9-ffffffff81005651: warn_bad_vsyscall.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810054f9)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:69
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81004fe0-ffffffff81005028: warn_bad_vsyscall (STB_LOCAL)
ffffffff810054f9-ffffffff81005551: warn_bad_vsyscall.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055a9)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810050a0-ffffffff810050e8: warn_bad_vsyscall (STB_LOCAL)
ffffffff810055a9-ffffffff810055f6: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005629)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81005120-ffffffff81005168: warn_bad_vsyscall (STB_LOCAL)
ffffffff81005629-ffffffff81005676: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810064ea)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81005ff0-ffffffff81006038: warn_bad_vsyscall (STB_LOCAL)
ffffffff810064ea-ffffffff81006537: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bd1af3)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81005220-ffffffff81005268: warn_bad_vsyscall (STB_LOCAL)
ffffffff81bd1af3-ffffffff81bd1b40: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bc3b94)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81005140-ffffffff81005188: warn_bad_vsyscall (STB_LOCAL)
ffffffff81bc3b94-ffffffff81bc3be1: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81c94be5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81005750-ffffffff81005798: warn_bad_vsyscall (STB_LOCAL)
ffffffff81c94be5-ffffffff81c94c32: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81e43e9b)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810048f0-ffffffff81004960: warn_bad_vsyscall (STB_LOCAL)
ffffffff81e43e9b-ffffffff81e43ee8: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810052e0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810052e0-ffffffff810053b3: warn_bad_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004b00)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81004b00-ffffffff81004bd3: warn_bad_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81007410)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81007410-ffffffff810074e3: warn_bad_vsyscall (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005629)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81005120-ffffffff81005168: warn_bad_vsyscall (STB_LOCAL)
ffffffff81005629-ffffffff81005676: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81003d09)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81003800-ffffffff81003848: warn_bad_vsyscall (STB_LOCAL)
ffffffff81003d09-ffffffff81003d56: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055e9)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff810050e0-ffffffff81005128: warn_bad_vsyscall (STB_LOCAL)
ffffffff810055e9-ffffffff81005636: warn_bad_vsyscall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void warn_bad_vsyscall(const char *level, struct pt_regs *regs, const char *message);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005749)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:73
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
**Symbols:**

```
ffffffff81005220-ffffffff81005268: warn_bad_vsyscall (STB_LOCAL)
ffffffff81005749-ffffffff81005796: warn_bad_vsyscall.cold (STB_LOCAL)
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
