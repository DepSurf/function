# Function: <code>pvclock_read_wallclock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81065260)
Location: arch/x86/kernel/pvclock.c:118
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81065260-ffffffff810652df: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81064fd0)
Location: arch/x86/kernel/pvclock.c:120
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81064fd0-ffffffff81065052: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81068500)
Location: arch/x86/kernel/pvclock.c:120
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81068500-ffffffff81068582: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81067830)
Location: arch/x86/kernel/pvclock.c:122
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81067830-ffffffff810678af: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8106ba90)
Location: arch/x86/kernel/pvclock.c:124
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff8106ba90-ffffffff8106bb0f: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8106e730)
Location: arch/x86/kernel/pvclock.c:124
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff8106e730-ffffffff8106e7b2: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81074750)
Location: arch/x86/kernel/pvclock.c:124
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81074750-ffffffff810747d2: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810782b0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff810782b0-ffffffff8107832b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81079320)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81079320-ffffffff8107939b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81080600)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81080600-ffffffff8108067b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81080210)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81080210-ffffffff8108028b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810810b0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff810810b0-ffffffff8108112b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81090050)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81090050-ffffffff810900cb: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810a0fb0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff810a0fb0-ffffffff810a1036: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810b8e30)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff810b8e30-ffffffff810b8eb6: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810bc000)
Location: arch/x86/kernel/pvclock.c:123
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff810bc000-ffffffff810bc086: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810c3180)
Location: arch/x86/kernel/pvclock.c:123
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff810c3180-ffffffff810c3206: pvclock_read_wallclock (STB_GLOBAL)
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
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81078320)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81078320-ffffffff8107839b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81067bd0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff81067bd0-ffffffff81067c4b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810782d0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff810782d0-ffffffff8107834b: pvclock_read_wallclock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock *wall_clock, struct pvclock_vcpu_time_info *vcpu_time, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8107a3d0)
Location: arch/x86/kernel/pvclock.c:113
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_read_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
**Symbols:**

```
ffffffff8107a3d0-ffffffff8107a44b: pvclock_read_wallclock (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
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
