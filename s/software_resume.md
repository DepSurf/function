# Function: <code>software_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810cf920)
Location: kernel/power/hibernate.c:741
Inline: True
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810cf920-ffffffff810cfc9d: software_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d4480)
Location: kernel/power/hibernate.c:787
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810d4480-ffffffff810d4766: software_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810db030)
Location: kernel/power/hibernate.c:789
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810db030-ffffffff810db315: software_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810da140)
Location: kernel/power/hibernate.c:784
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810da140-ffffffff810da40a: software_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e2300)
Location: kernel/power/hibernate.c:787
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810e2300-ffffffff810e2599: software_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:794
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810ea700-ffffffff810ea908: software_resume (STB_LOCAL)
ffffffff810eadca-ffffffff810eae4d: software_resume.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:796
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810f5d30-ffffffff810f5f38: software_resume (STB_LOCAL)
ffffffff810f63fd-ffffffff810f6480: software_resume.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:801
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810fe2c0-ffffffff810fe4ce: software_resume (STB_LOCAL)
ffffffff810fe9a0-ffffffff810fea26: software_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:802
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff8110a6f0-ffffffff8110a919: software_resume (STB_LOCAL)
ffffffff8110adec-ffffffff8110ae72: software_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:814
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff81115360-ffffffff81115539: software_resume (STB_LOCAL)
ffffffff811159ee-ffffffff81115ab6: software_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111f08)
Location: kernel/power/hibernate.c:909
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff81111e40-ffffffff81111e73: software_resume (STB_LOCAL)
ffffffff81111cf0-ffffffff81111e34: software_resume.part.0 (STB_LOCAL)
ffffffff81bdf281-ffffffff81bdf33a: software_resume.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81112928)
Location: kernel/power/hibernate.c:909
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff81112860-ffffffff81112893: software_resume (STB_LOCAL)
ffffffff81112710-ffffffff81112854: software_resume.part.0 (STB_LOCAL)
ffffffff81bd13d1-ffffffff81bd148a: software_resume.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (ffffffff8113295c)
Location: kernel/power/hibernate.c:912
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff81132890-ffffffff811328cc: software_resume (STB_LOCAL)
ffffffff81132740-ffffffff81132884: software_resume.part.0 (STB_LOCAL)
ffffffff81ca9f3a-ffffffff81ca9ff3: software_resume.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811548a4)
Location: kernel/power/hibernate.c:915
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff811547b0-ffffffff81154807: software_resume (STB_LOCAL)
ffffffff81154590-ffffffff811547ae: software_resume.part.0 (STB_LOCAL)
ffffffff81e5a00e-ffffffff81e5a1c7: software_resume.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81184382)
Location: kernel/power/hibernate.c:921
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff81184280-ffffffff811842d7: software_resume (STB_LOCAL)
ffffffff81183ed0-ffffffff81184262: software_resume.part.0 (STB_LOCAL)
ffffffff820584ce-ffffffff82058533: software_resume.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81194d30)
Location: kernel/power/hibernate.c:938
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume_initcall
```
**Symbols:**

```
ffffffff81194d30-ffffffff81194f4f: software_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a3710)
Location: kernel/power/hibernate.c:944
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:software_resume_initcall
```
**Symbols:**

```
ffffffff811a3710-ffffffff811a392c: software_resume (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c03bce04)
Location: kernel/power/hibernate.c:802
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
c03bce04-c03bd0e0: software_resume (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:802
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff81102950-ffffffff81102b79: software_resume (STB_LOCAL)
ffffffff8110304c-ffffffff811030d2: software_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:802
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff810f3bc0-ffffffff810f3de9: software_resume (STB_LOCAL)
ffffffff810f42ac-ffffffff810f4332: software_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:802
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff81100bc0-ffffffff81100de9: software_resume (STB_LOCAL)
ffffffff811012bc-ffffffff81101342: software_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int software_resume();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:802
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
```
**Symbols:**

```
ffffffff8110bf90-ffffffff8110c1b9: software_resume (STB_LOCAL)
ffffffff8110c68c-ffffffff8110c712: software_resume.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
