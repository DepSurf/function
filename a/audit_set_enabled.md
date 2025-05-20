# Function: <code>audit_set_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811235e8)
Location: kernel/audit.c:346
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112b504)
Location: kernel/audit.c:344
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811351d1)
Location: kernel/audit.c:350
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811366ab)
Location: kernel/audit.c:415
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811421e0)
Location: kernel/audit.c:415
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811421e0-ffffffff8114221e: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150bb0)
Location: kernel/audit.c:458
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81150bb0-ffffffff81150bee: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d850)
Location: kernel/audit.c:454
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8115d850-ffffffff8115d88e: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169f80)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81169f80-ffffffff81169fbe: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175e20)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81175e20-ffffffff81175e5e: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187a70)
Location: kernel/audit.c:443
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81187a70-ffffffff81187ae5: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184de0)
Location: kernel/audit.c:448
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81184de0-ffffffff81184e55: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185c70)
Location: kernel/audit.c:448
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81185c70-ffffffff81185ce5: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:448
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811ae050-ffffffff811ae0e0: audit_set_enabled (STB_LOCAL)
ffffffff81cb34f2-ffffffff81cb3506: audit_set_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:449
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811dfec0-ffffffff811dff81: audit_set_enabled (STB_LOCAL)
ffffffff81e64326-ffffffff81e6433b: audit_set_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:447
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81225c10-ffffffff81225cd1: audit_set_enabled (STB_LOCAL)
ffffffff8205c5a7-ffffffff8205c5bc: audit_set_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:447
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8123c1f0-ffffffff8123c2b1: audit_set_enabled (STB_LOCAL)
ffffffff820daf04-ffffffff820daf19: audit_set_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:447
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff812560c0-ffffffff81256181: audit_set_enabled (STB_LOCAL)
ffffffff821b6c2b-ffffffff821b6c40: audit_set_enabled.cold (STB_LOCAL)
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
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eae08)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffff8000101eae08-ffff8000101eae70: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042aa50)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
c042aa50-c042aab0: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025c2f0)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
c00000000025c2f0-c00000000025c378: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f718)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffe00015f718-ffffffe00015f774: audit_set_enabled (STB_LOCAL)
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
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e440)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8116e440-ffffffff8116e47e: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811615e0)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811615e0-ffffffff8116161e: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116c210)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8116c210-ffffffff8116c24e: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_set_enabled(u32 state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811799d0)
Location: kernel/audit.c:441
Inline: False
Direct callers:
  - kernel/audit.c:audit_enable
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811799d0-ffffffff81179a0e: audit_set_enabled (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
