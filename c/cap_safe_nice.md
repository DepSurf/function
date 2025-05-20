# Function: <code>cap_safe_nice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8133a6c0)
Location: security/commoncap.c:819
Inline: True
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff8133a6c0-ffffffff8133a751: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8136fd70)
Location: security/commoncap.c:825
Inline: True
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff8136fd70-ffffffff8136fdc9: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81386590)
Location: security/commoncap.c:820
Inline: True
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff81386590-ffffffff813865e9: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139b090)
Location: security/commoncap.c:1048
Inline: True
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff8139b090-ffffffff8139b0ee: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813c0720)
Location: security/commoncap.c:1085
Inline: True
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff813c0720-ffffffff813c077e: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813f16a0)
Location: security/commoncap.c:1091
Inline: True
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff813f16a0-ffffffff813f16fa: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8140c970)
Location: security/commoncap.c:1086
Inline: True
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff8140c970-ffffffff8140c9ca: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81439af0)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setnice
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff81439af0-ffffffff81439b49: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81453960)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setnice
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff81453960-ffffffff814539b9: cap_safe_nice (STB_LOCAL)
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
In security/commoncap.c (ffffffff814a6015)
Location: security/commoncap.c:1085
Inline: True
Inline callers:
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c3530)
Location: security/commoncap.c:1103
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff814c3530-ffffffff814c35a7: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c99a0)
Location: security/commoncap.c:1175
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff814c99a0-ffffffff814c9a15: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815224c0)
Location: security/commoncap.c:1175
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff815224c0-ffffffff81522535: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815b5fb0)
Location: security/commoncap.c:1178
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff815b5fb0-ffffffff815b6044: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff816610c0)
Location: security/commoncap.c:1178
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff816610c0-ffffffff81661154: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81699380)
Location: security/commoncap.c:1173
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff81699380-ffffffff81699409: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff816d5a30)
Location: security/commoncap.c:1173
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff816d5a30-ffffffff816d5ab9: cap_safe_nice (STB_LOCAL)
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
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053e9b0)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffff80001053e9b0-ffff80001053ea24: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f4988)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
c06f4988-c06f49fc: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c00000000068f0f0)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setnice
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
c00000000068f0f0-c00000000068f180: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039c07a)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffe00039c07a-ffffffe00039c0e4: cap_safe_nice (STB_LOCAL)
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
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8144bf40)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setnice
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff8144bf40-ffffffff8144bf99: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143c990)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setnice
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff8143c990-ffffffff8143c9e9: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81447fe0)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setnice
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff81447fe0-ffffffff81448039: cap_safe_nice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cap_safe_nice(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8145f330)
Location: security/commoncap.c:1083
Inline: False
Direct callers:
  - security/commoncap.c:cap_task_setnice
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
```
**Symbols:**

```
ffffffff8145f330-ffffffff8145f3ae: cap_safe_nice (STB_LOCAL)
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
