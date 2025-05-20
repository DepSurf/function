# Function: <code>count_semcnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81326d10)
Location: ipc/sem.c:1050
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81326d10-ffffffff81326ded: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135c410)
Location: ipc/sem.c:1046
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8135c410-ffffffff8135c4f4: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81372ab0)
Location: ipc/sem.c:1042
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81372ab0-ffffffff81372b94: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81385e90)
Location: ipc/sem.c:1053
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81385e90-ffffffff81385f5c: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813aa7a0)
Location: ipc/sem.c:1056
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff813aa7a0-ffffffff813aa86c: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813d9630)
Location: ipc/sem.c:1092
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff813d9630-ffffffff813d9701: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f3c80)
Location: ipc/sem.c:1091
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff813f3c80-ffffffff813f3d51: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814200d0)
Location: ipc/sem.c:1087
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814200d0-ffffffff814201a1: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81439ed0)
Location: ipc/sem.c:1087
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81439ed0-ffffffff81439fa1: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1103
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8148a060-ffffffff8148a15c: count_semcnt (STB_LOCAL)
ffffffff8148eb15-ffffffff8148eb64: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1102
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814a7680-ffffffff814a777c: count_semcnt (STB_LOCAL)
ffffffff81befacf-ffffffff81befb1e: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1104
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814ad5c0-ffffffff814ad6bc: count_semcnt (STB_LOCAL)
ffffffff81be1b76-ffffffff81be1bc5: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1107
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81505a90-ffffffff81505b96: count_semcnt (STB_LOCAL)
ffffffff81cd2a34-ffffffff81cd2ac7: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1106
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81597730-ffffffff81597849: count_semcnt (STB_LOCAL)
ffffffff81e85b8f-ffffffff81e85c24: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1106
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81640880-ffffffff816409ec: count_semcnt (STB_LOCAL)
ffffffff82072d5f-ffffffff82072d9d: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1106
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81678dd0-ffffffff81678f43: count_semcnt (STB_LOCAL)
ffffffff820f29b6-ffffffff820f29f2: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1106
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff816b51c0-ffffffff816b5333: count_semcnt (STB_LOCAL)
ffffffff821cfc66-ffffffff821cfca2: count_semcnt.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff8000105239d8)
Location: ipc/sem.c:1087
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06de11c)
Location: ipc/sem.c:1087
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066d758)
Location: ipc/sem.c:1087
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000388922)
Location: ipc/sem.c:1087
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
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
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814324b0)
Location: ipc/sem.c:1087
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814324b0-ffffffff81432581: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81422f30)
Location: ipc/sem.c:1087
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81422f30-ffffffff81423001: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142e650)
Location: ipc/sem.c:1087
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8142e650-ffffffff8142e721: count_semcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int count_semcnt(struct sem_array *sma, ushort semnum, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814459b0)
Location: ipc/sem.c:1087
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814459b0-ffffffff81445a81: count_semcnt (STB_LOCAL)
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
