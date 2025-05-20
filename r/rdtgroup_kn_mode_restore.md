# Function: <code>rdtgroup_kn_mode_restore</code>

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
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810582f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff810582f0-ffffffff81058417: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b880)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1569
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105b880-ffffffff8105b99d: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c190)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105c190-ffffffff8105c2ad: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062220)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1658
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict
```
**Symbols:**

```
ffffffff81062220-ffffffff8106233d: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060770)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict
```
**Symbols:**

```
ffffffff81060770-ffffffff8106088e: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060880)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81060880-ffffffff8106099e: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069a90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1678
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81069a90-ffffffff81069bae: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81076d90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1678
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81076d90-ffffffff81076ec3: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810878c0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1683
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff810878c0-ffffffff810879f3: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108a820)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1964
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8108a820-ffffffff8108a951: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091940)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2055
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81091940-ffffffff81091a71: rdtgroup_kn_mode_restore (STB_GLOBAL)
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
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bd10)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105bd10-ffffffff8105be2d: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104bee0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8104bee0-ffffffff8104bffd: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c140)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105c140-ffffffff8105c25d: rdtgroup_kn_mode_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restore(struct rdtgroup *r, const char *name, umode_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d650)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105d650-ffffffff8105d76d: rdtgroup_kn_mode_restore (STB_GLOBAL)
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
