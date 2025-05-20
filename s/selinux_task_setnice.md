# Function: <code>selinux_task_setnice</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3830
Inline: False
```
**Symbols:**

```
ffffffff8137cc60-ffffffff8137cc75: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3902
Inline: False
```
**Symbols:**

```
ffffffff81393710-ffffffff81393725: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a4350)
Location: security/selinux/hooks.c:3863
Inline: False
```
**Symbols:**

```
ffffffff813a4350-ffffffff813a439a: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ca430)
Location: security/selinux/hooks.c:3878
Inline: False
```
**Symbols:**

```
ffffffff813ca430-ffffffff813ca47a: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813f97f0)
Location: security/selinux/hooks.c:4102
Inline: False
```
**Symbols:**

```
ffffffff813f97f0-ffffffff813f983a: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814156b0)
Location: security/selinux/hooks.c:3822
Inline: False
```
**Symbols:**

```
ffffffff814156b0-ffffffff81415702: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814430f0)
Location: security/selinux/hooks.c:4010
Inline: False
```
**Symbols:**

```
ffffffff814430f0-ffffffff81443142: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145cc30)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
ffffffff8145cc30-ffffffff8145cc8a: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814afee0)
Location: security/selinux/hooks.c:4061
Inline: True
```
**Symbols:**

```
ffffffff814afee0-ffffffff814aff3a: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d0d80)
Location: security/selinux/hooks.c:4077
Inline: False
```
**Symbols:**

```
ffffffff814d0d80-ffffffff814d0de9: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d71c0)
Location: security/selinux/hooks.c:4241
Inline: True
```
**Symbols:**

```
ffffffff814d71c0-ffffffff814d7229: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152fe30)
Location: security/selinux/hooks.c:4226
Inline: True
```
**Symbols:**

```
ffffffff8152fe30-ffffffff8152fe99: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c6d70)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffff815c6d70-ffffffff815c6df0: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81673a90)
Location: security/selinux/hooks.c:4140
Inline: False
```
**Symbols:**

```
ffffffff81673a90-ffffffff81673b10: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ac1b0)
Location: security/selinux/hooks.c:4110
Inline: False
```
**Symbols:**

```
ffffffff816ac1b0-ffffffff816ac225: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e95a0)
Location: security/selinux/hooks.c:4198
Inline: False
```
**Symbols:**

```
ffffffff816e95a0-ffffffff816e961b: selinux_task_setnice (STB_LOCAL)
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
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff8000105498c8)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
ffff8000105498c8-ffff800010549938: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06ff5fc)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
c06ff5fc-c06ff67c: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a1010)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
c0000000006a1010-c0000000006a1088: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a4706)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
ffffffe0003a4706-ffffffe0003a475e: selinux_task_setnice (STB_LOCAL)
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
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81455210)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
ffffffff81455210-ffffffff8145526a: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445c50)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
ffffffff81445c50-ffffffff81445caa: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814512b0)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
ffffffff814512b0-ffffffff8145130a: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81469ea0)
Location: security/selinux/hooks.c:4068
Inline: False
```
**Symbols:**

```
ffffffff81469ea0-ffffffff81469f11: selinux_task_setnice (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
