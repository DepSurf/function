# Function: <code>virt_efi_set_wakeup_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4dd0)
Location: drivers/firmware/efi/runtime-wrappers.c:139
Inline: False
```
**Symbols:**

```
ffffffff816d4dd0-ffffffff816d4e51: virt_efi_set_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81739000)
Location: drivers/firmware/efi/runtime-wrappers.c:123
Inline: False
```
**Symbols:**

```
ffffffff81739000-ffffffff817390f0: virt_efi_set_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176c190)
Location: drivers/firmware/efi/runtime-wrappers.c:128
Inline: True
```
**Symbols:**

```
ffffffff8176c190-ffffffff8176c2ae: virt_efi_set_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a550)
Location: drivers/firmware/efi/runtime-wrappers.c:128
Inline: True
```
**Symbols:**

```
ffffffff8178a550-ffffffff8178a65f: virt_efi_set_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800ae0)
Location: drivers/firmware/efi/runtime-wrappers.c:128
Inline: True
```
**Symbols:**

```
ffffffff81800ae0-ffffffff81800c1c: virt_efi_set_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8184a010)
Location: drivers/firmware/efi/runtime-wrappers.c:128
Inline: True
```
**Symbols:**

```
ffffffff8184a010-ffffffff8184a109: virt_efi_set_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:275
Inline: False
```
**Symbols:**

```
ffffffff81876130-ffffffff8187626c: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff818772b6-ffffffff818772ed: virt_efi_set_wakeup_time.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff818ba340-ffffffff818ba47d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff818bb746-ffffffff818bb77d: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff818ecde0-ffffffff818ecf1d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff818ee1e6-ffffffff818ee21d: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff819c0530-ffffffff819c066d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff819c1c48-ffffffff819c1c7f: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff819c0f50-ffffffff819c108d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff81c2ca1f-ffffffff81c2ca56: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff819a55f0-ffffffff819a572d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff81c1ec4d-ffffffff81c1ec84: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff81a52930-ffffffff81a52a79: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff81d301fc-ffffffff81d30239: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff81bc21f0-ffffffff81bc2343: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff81efc761-ffffffff81efc79e: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:289
Inline: False
```
**Symbols:**

```
ffffffff81d66d90-ffffffff81d66f2b: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff820a9f22-ffffffff820a9f36: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:289
Inline: False
```
**Symbols:**

```
ffffffff81dd1ea0-ffffffff81dd203b: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff8212b2d0-ffffffff8212b2e4: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a780)
Location: drivers/firmware/efi/runtime-wrappers.c:382
Inline: True
```
**Symbols:**

```
ffffffff81e8a780-ffffffff81e8a839: virt_efi_set_wakeup_time (STB_LOCAL)
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
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b600d0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffff800010b600d0-ffff800010b60228: virt_efi_set_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3f638)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
c0c3f638-c0c3f780: virt_efi_set_wakeup_time (STB_LOCAL)
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
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff8188e9c0-ffffffff8188eafd: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff8188fdc6-ffffffff8188fdfd: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff818474e0-ffffffff8184761d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff81848876-ffffffff818488ad: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff818e1c40-ffffffff818e1d7d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff818e3046-ffffffff818e307d: virt_efi_set_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_wakeup_time(efi_bool_t enabled, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff818fe6e0-ffffffff818fe81d: virt_efi_set_wakeup_time (STB_LOCAL)
ffffffff818ffc86-ffffffff818ffcbd: virt_efi_set_wakeup_time.cold (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
