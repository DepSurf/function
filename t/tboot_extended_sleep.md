# Function: <code>tboot_extended_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103dee0)
Location: arch/x86/kernel/tboot.c:304
Inline: False
```
**Symbols:**

```
ffffffff8103dee0-ffffffff8103df09: tboot_extended_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103dd00)
Location: arch/x86/kernel/tboot.c:298
Inline: False
```
**Symbols:**

```
ffffffff8103dd00-ffffffff8103dd29: tboot_extended_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103d5c0)
Location: arch/x86/kernel/tboot.c:298
Inline: False
```
**Symbols:**

```
ffffffff8103d5c0-ffffffff8103d5e9: tboot_extended_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103b610)
Location: arch/x86/kernel/tboot.c:302
Inline: False
```
**Symbols:**

```
ffffffff8103b610-ffffffff8103b639: tboot_extended_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e030)
Location: arch/x86/kernel/tboot.c:313
Inline: False
```
**Symbols:**

```
ffffffff8103e030-ffffffff8103e059: tboot_extended_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:313
Inline: False
```
**Symbols:**

```
ffffffff8103f5e0-ffffffff8103f5fb: tboot_extended_sleep (STB_LOCAL)
ffffffff8103fb83-ffffffff8103fb99: tboot_extended_sleep.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:313
Inline: False
```
**Symbols:**

```
ffffffff81040be0-ffffffff81040bfb: tboot_extended_sleep (STB_LOCAL)
ffffffff81041183-ffffffff81041199: tboot_extended_sleep.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:300
Inline: False
```
**Symbols:**

```
ffffffff810432c0-ffffffff810432db: tboot_extended_sleep (STB_LOCAL)
ffffffff81043853-ffffffff81043869: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:300
Inline: False
```
**Symbols:**

```
ffffffff81043a20-ffffffff81043a3b: tboot_extended_sleep (STB_LOCAL)
ffffffff81043fa3-ffffffff81043fb9: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:302
Inline: False
```
**Symbols:**

```
ffffffff810472d0-ffffffff810472eb: tboot_extended_sleep (STB_LOCAL)
ffffffff81047903-ffffffff81047919: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:303
Inline: False
```
**Symbols:**

```
ffffffff81046b20-ffffffff81046b3b: tboot_extended_sleep (STB_LOCAL)
ffffffff81bd4b87-ffffffff81bd4b9d: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:311
Inline: False
```
**Symbols:**

```
ffffffff81048550-ffffffff81048566: tboot_extended_sleep (STB_LOCAL)
ffffffff81bc701c-ffffffff81bc7033: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:311
Inline: False
```
**Symbols:**

```
ffffffff8104ee90-ffffffff8104eea6: tboot_extended_sleep (STB_LOCAL)
ffffffff81c9a601-ffffffff81c9a618: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:310
Inline: False
```
**Symbols:**

```
ffffffff8105a0e0-ffffffff8105a0fc: tboot_extended_sleep (STB_LOCAL)
ffffffff81e49a66-ffffffff81e49a83: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81067b80)
Location: arch/x86/kernel/tboot.c:309
Inline: False
```
**Symbols:**

```
ffffffff81067b80-ffffffff81067bb5: tboot_extended_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81069430)
Location: arch/x86/kernel/tboot.c:309
Inline: False
```
**Symbols:**

```
ffffffff81069430-ffffffff81069465: tboot_extended_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810708a0)
Location: arch/x86/kernel/tboot.c:309
Inline: False
```
**Symbols:**

```
ffffffff810708a0-ffffffff810708d5: tboot_extended_sleep (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:300
Inline: False
```
**Symbols:**

```
ffffffff81043ba0-ffffffff81043bbb: tboot_extended_sleep (STB_LOCAL)
ffffffff81044123-ffffffff81044139: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:300
Inline: False
```
**Symbols:**

```
ffffffff810331d0-ffffffff810331eb: tboot_extended_sleep (STB_LOCAL)
ffffffff81033743-ffffffff81033759: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:300
Inline: False
```
**Symbols:**

```
ffffffff810439e0-ffffffff810439fb: tboot_extended_sleep (STB_LOCAL)
ffffffff81043f63-ffffffff81043f79: tboot_extended_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tboot_extended_sleep(u8 sleep_state, u32 val_a, u32 val_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:300
Inline: False
```
**Symbols:**

```
ffffffff81044de0-ffffffff81044dfb: tboot_extended_sleep (STB_LOCAL)
ffffffff81045363-ffffffff81045379: tboot_extended_sleep.cold (STB_LOCAL)
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
