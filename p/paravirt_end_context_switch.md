# Function: <code>paravirt_end_context_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064e20)
Location: arch/x86/kernel/paravirt.c:295
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81064e20-ffffffff81064e5a: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064bd0)
Location: arch/x86/kernel/paravirt.c:278
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81064bd0-ffffffff81064c0a: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810680a0)
Location: arch/x86/kernel/paravirt.c:278
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff810680a0-ffffffff810680d5: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810673c0)
Location: arch/x86/kernel/paravirt.c:278
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff810673c0-ffffffff810673f5: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b610)
Location: arch/x86/kernel/paravirt.c:288
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff8106b610-ffffffff8106b647: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106e2e0)
Location: arch/x86/kernel/paravirt.c:294
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff8106e2e0-ffffffff8106e318: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810742b0)
Location: arch/x86/kernel/paravirt.c:274
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff810742b0-ffffffff810742e8: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077e00)
Location: arch/x86/kernel/paravirt.c:262
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81077e00-ffffffff81077e38: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078e70)
Location: arch/x86/kernel/paravirt.c:262
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81078e70-ffffffff81078ea8: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080160)
Location: arch/x86/kernel/paravirt.c:244
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81080160-ffffffff81080194: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fd80)
Location: arch/x86/kernel/paravirt.c:244
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff8107fd80-ffffffff8107fdb4: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080e40)
Location: arch/x86/kernel/paravirt.c:212
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81080e40-ffffffff81080e74: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108fdb0)
Location: arch/x86/kernel/paravirt.c:212
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff8108fdb0-ffffffff8108fde4: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0c60)
Location: arch/x86/kernel/paravirt.c:206
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff810a0c60-ffffffff810a0ce3: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b89e0)
Location: arch/x86/kernel/paravirt.c:189
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff810b89e0-ffffffff810b8a66: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bbbb0)
Location: arch/x86/kernel/paravirt.c:190
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff810bbbb0-ffffffff810bbc36: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077e70)
Location: arch/x86/kernel/paravirt.c:262
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81077e70-ffffffff81077ea8: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077e20)
Location: arch/x86/kernel/paravirt.c:262
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81077e20-ffffffff81077e58: paravirt_end_context_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void paravirt_end_context_switch(struct task_struct *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079f00)
Location: arch/x86/kernel/paravirt.c:262
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
**Symbols:**

```
ffffffff81079f00-ffffffff81079f54: paravirt_end_context_switch (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
