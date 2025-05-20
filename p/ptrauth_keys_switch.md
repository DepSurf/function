# Function: <code>ptrauth_keys_switch</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ptrauth_keys_switch(struct ptrauth_keys *keys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010088cf8)
Location: arch/arm64/include/asm/pointer_auth.h:53
Inline: True
Direct callers:
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:__switch_to
```
```
In arch/arm64/kernel/pointer_auth.c (ffff8000100ac260)
Location: arch/arm64/include/asm/pointer_auth.h:53
Inline: True
Direct callers:
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
```
**Symbols:**

```
ffff800010088cf8-ffff800010088dac: ptrauth_keys_switch (STB_LOCAL)
ffff8000100ac260-ffff8000100ac314: ptrauth_keys_switch (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
