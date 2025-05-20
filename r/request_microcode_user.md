# Function: <code>request_microcode_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104db50)
Location: arch/x86/kernel/cpu/microcode/intel.c:1021
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e0e0)
Location: arch/x86/kernel/cpu/microcode/amd.c:931
Inline: False
```
**Symbols:**

```
ffffffff8104db50-ffffffff8104db67: request_microcode_user (STB_LOCAL)
ffffffff8104e0e0-ffffffff8104e0ed: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dae0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1079
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e270)
Location: arch/x86/kernel/cpu/microcode/amd.c:941
Inline: False
```
**Symbols:**

```
ffffffff8104dae0-ffffffff8104daf7: request_microcode_user (STB_LOCAL)
ffffffff8104e270-ffffffff8104e27d: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050070)
Location: arch/x86/kernel/cpu/microcode/intel.c:930
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810508f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:943
Inline: False
```
**Symbols:**

```
ffffffff81050070-ffffffff81050087: request_microcode_user (STB_LOCAL)
ffffffff810508f0-ffffffff810508fd: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810500e0)
Location: arch/x86/kernel/cpu/microcode/intel.c:950
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810507f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:756
Inline: False
```
**Symbols:**

```
ffffffff810500e0-ffffffff810500f7: request_microcode_user (STB_LOCAL)
ffffffff810507f0-ffffffff810507fd: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053ae0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1002
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054400)
Location: arch/x86/kernel/cpu/microcode/amd.c:771
Inline: False
```
**Symbols:**

```
ffffffff81053ae0-ffffffff81053b23: request_microcode_user (STB_LOCAL)
ffffffff81054400-ffffffff81054410: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056760)
Location: arch/x86/kernel/cpu/microcode/intel.c:1010
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810571d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:779
Inline: False
```
**Symbols:**

```
ffffffff81056760-ffffffff810567a3: request_microcode_user (STB_LOCAL)
ffffffff810571d0-ffffffff810571e0: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053df0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1010
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054790)
Location: arch/x86/kernel/cpu/microcode/amd.c:925
Inline: False
```
**Symbols:**

```
ffffffff81053df0-ffffffff81053e33: request_microcode_user (STB_LOCAL)
ffffffff81054790-ffffffff810547a0: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056fb0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1000
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810579e0)
Location: arch/x86/kernel/cpu/microcode/amd.c:923
Inline: False
```
**Symbols:**

```
ffffffff81056fb0-ffffffff81057039: request_microcode_user (STB_LOCAL)
ffffffff810579e0-ffffffff810579f0: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057880)
Location: arch/x86/kernel/cpu/microcode/intel.c:1000
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810582b0)
Location: arch/x86/kernel/cpu/microcode/amd.c:923
Inline: False
```
**Symbols:**

```
ffffffff81057880-ffffffff81057909: request_microcode_user (STB_LOCAL)
ffffffff810582b0-ffffffff810582c0: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cb40)
Location: arch/x86/kernel/cpu/microcode/intel.c:1001
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105d3f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:923
Inline: False
```
**Symbols:**

```
ffffffff8105cb40-ffffffff8105cbc9: request_microcode_user (STB_LOCAL)
ffffffff8105d3f0-ffffffff8105d400: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b3c0)
Location: arch/x86/kernel/cpu/microcode/intel.c:958
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105ba90)
Location: arch/x86/kernel/cpu/microcode/amd.c:922
Inline: False
```
**Symbols:**

```
ffffffff8105b3c0-ffffffff8105b449: request_microcode_user (STB_LOCAL)
ffffffff8105ba90-ffffffff8105baa0: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105bd70)
Location: arch/x86/kernel/cpu/microcode/intel.c:958
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c450)
Location: arch/x86/kernel/cpu/microcode/amd.c:922
Inline: False
```
**Symbols:**

```
ffffffff8105bd70-ffffffff8105bdf9: request_microcode_user (STB_LOCAL)
ffffffff8105c450-ffffffff8105c460: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810653f0)
Location: arch/x86/kernel/cpu/microcode/intel.c:958
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81065b10)
Location: arch/x86/kernel/cpu/microcode/amd.c:922
Inline: False
```
**Symbols:**

```
ffffffff810653f0-ffffffff81065479: request_microcode_user (STB_LOCAL)
ffffffff81065b10-ffffffff81065b20: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071ec0)
Location: arch/x86/kernel/cpu/microcode/intel.c:920
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810725e0)
Location: arch/x86/kernel/cpu/microcode/amd.c:928
Inline: False
```
**Symbols:**

```
ffffffff81071ec0-ffffffff81071f8c: request_microcode_user (STB_LOCAL)
ffffffff810725e0-ffffffff810725f4: request_microcode_user (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057400)
Location: arch/x86/kernel/cpu/microcode/intel.c:1000
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057e30)
Location: arch/x86/kernel/cpu/microcode/amd.c:923
Inline: False
```
**Symbols:**

```
ffffffff81057400-ffffffff81057489: request_microcode_user (STB_LOCAL)
ffffffff81057e30-ffffffff81057e40: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810475f0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1000
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048020)
Location: arch/x86/kernel/cpu/microcode/amd.c:923
Inline: False
```
**Symbols:**

```
ffffffff810475f0-ffffffff81047679: request_microcode_user (STB_LOCAL)
ffffffff81048020-ffffffff81048030: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057830)
Location: arch/x86/kernel/cpu/microcode/intel.c:1000
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058260)
Location: arch/x86/kernel/cpu/microcode/amd.c:923
Inline: False
```
**Symbols:**

```
ffffffff81057830-ffffffff810578b9: request_microcode_user (STB_LOCAL)
ffffffff81058260-ffffffff81058270: request_microcode_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058cd0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1000
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059700)
Location: arch/x86/kernel/cpu/microcode/amd.c:923
Inline: False
```
**Symbols:**

```
ffffffff81058cd0-ffffffff81058d59: request_microcode_user (STB_LOCAL)
ffffffff81059700-ffffffff81059710: request_microcode_user (STB_LOCAL)
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
