# Function: <code>MP_lintsrc_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff81f7044d)
Location: arch/x86/kernel/mpparse.c:141
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff81f7044d-ffffffff81f70489: MP_lintsrc_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff81f993ec)
Location: arch/x86/kernel/mpparse.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff81f98b94-ffffffff81f98bd0: MP_lintsrc_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff81fd48c2)
Location: arch/x86/kernel/mpparse.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff81fd405d-ffffffff81fd4099: MP_lintsrc_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff820b5594)
Location: arch/x86/kernel/mpparse.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff820b4d33-ffffffff820b4d74: MP_lintsrc_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff826bbd68)
Location: arch/x86/kernel/mpparse.c:141
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff826bb43f-ffffffff826bb480: MP_lintsrc_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff826e4dcf)
Location: arch/x86/kernel/mpparse.c:141
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff826e4dcf-ffffffff826e4e1a: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff8289b8a7)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff8289b8a7-ffffffff8289b8f2: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b3673)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff828b3673-ffffffff828b36be: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b6aca)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff828b6aca-ffffffff828b6b15: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82cdbb78)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:smp_read_mpc
```
**Symbols:**

```
ffffffff82cdbb78-ffffffff82cdbbc3: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82fc7fce)
Location: arch/x86/kernel/mpparse.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff82fc7fce-ffffffff82fc8019: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff831d2949)
Location: arch/x86/kernel/mpparse.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff831d2949-ffffffff831d2994: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff832b52a1)
Location: arch/x86/kernel/mpparse.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff832b52a1-ffffffff832b52ec: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83466a5f)
Location: arch/x86/kernel/mpparse.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff83466a5f-ffffffff83466ad2: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83e8a780)
Location: arch/x86/kernel/mpparse.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
```
**Symbols:**

```
ffffffff83e8a780-ffffffff83e8a7f4: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff836ade50)
Location: arch/x86/kernel/mpparse.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
```
**Symbols:**

```
ffffffff836ade50-ffffffff836adec4: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff838de3e0)
Location: arch/x86/kernel/mpparse.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
```
**Symbols:**

```
ffffffff838de3e0-ffffffff838de454: MP_lintsrc_info (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828a4ad1)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff828a4ad1-ffffffff828a4b1c: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff8289cc13)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff8289cc13-ffffffff8289cc5e: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b79e1)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff828b79e1-ffffffff828b7a2c: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void MP_lintsrc_info(struct mpc_lintsrc *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b7ae2)
Location: arch/x86/kernel/mpparse.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
```
**Symbols:**

```
ffffffff828b7ae2-ffffffff828b7b2d: MP_lintsrc_info (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
