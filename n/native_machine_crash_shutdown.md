# Function: <code>native_machine_crash_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105d780)
Location: arch/x86/kernel/crash.c:145
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff8105d780-ffffffff8105d943: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105d6e0)
Location: arch/x86/kernel/crash.c:150
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff8105d6e0-ffffffff8105d853: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81060760)
Location: arch/x86/kernel/crash.c:166
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81060760-ffffffff810608da: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105f7e0)
Location: arch/x86/kernel/crash.c:167
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff8105f7e0-ffffffff8105f949: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81063810)
Location: arch/x86/kernel/crash.c:167
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81063810-ffffffff81063994: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810664c0)
Location: arch/x86/kernel/crash.c:136
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810664c0-ffffffff81066637: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8106c4d0)
Location: arch/x86/kernel/crash.c:137
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff8106c4d0-ffffffff8106c656: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810704d0)
Location: arch/x86/kernel/crash.c:129
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810704d0-ffffffff81070655: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810714d0)
Location: arch/x86/kernel/crash.c:129
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810714d0-ffffffff81071655: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810785c0)
Location: arch/x86/kernel/crash.c:144
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810785c0-ffffffff8107875c: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810785c0)
Location: arch/x86/kernel/crash.c:144
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810785c0-ffffffff81078761: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81079480)
Location: arch/x86/kernel/crash.c:144
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvm.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81079480-ffffffff81079600: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810874e0)
Location: arch/x86/kernel/crash.c:131
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvm.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810874e0-ffffffff81087660: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81097620)
Location: arch/x86/kernel/crash.c:131
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvm.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81097620-ffffffff810977c9: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810adb00)
Location: arch/x86/kernel/crash.c:121
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvm.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810adb00-ffffffff810adba9: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b0b00)
Location: arch/x86/kernel/crash.c:121
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvm.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810b0b00-ffffffff810b0ba9: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b7c60)
Location: arch/x86/kernel/crash.c:95
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvm.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810b7c60-ffffffff810b7cee: native_machine_crash_shutdown (STB_GLOBAL)
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
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810704d0)
Location: arch/x86/kernel/crash.c:129
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810704d0-ffffffff81070655: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810604e0)
Location: arch/x86/kernel/crash.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810604e0-ffffffff81060667: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810704d0)
Location: arch/x86/kernel/crash.c:129
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810704d0-ffffffff81070655: native_machine_crash_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_machine_crash_shutdown(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810724e0)
Location: arch/x86/kernel/crash.c:129
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810724e0-ffffffff8107266f: native_machine_crash_shutdown (STB_GLOBAL)
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
