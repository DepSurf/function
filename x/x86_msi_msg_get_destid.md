# Function: <code>x86_msi_msg_get_destid</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 x86_msi_msg_get_destid(struct msi_msg *msg, bool extid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106dc90)
Location: arch/x86/kernel/apic/apic.c:2539
Inline: False
```
**Symbols:**

```
ffffffff8106dc90-ffffffff8106dcaf: x86_msi_msg_get_destid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 x86_msi_msg_get_destid(struct msi_msg *msg, bool extid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106e700)
Location: arch/x86/kernel/apic/apic.c:2547
Inline: False
```
**Symbols:**

```
ffffffff8106e700-ffffffff8106e71f: x86_msi_msg_get_destid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 x86_msi_msg_get_destid(struct msi_msg *msg, bool extid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107a050)
Location: arch/x86/kernel/apic/apic.c:2544
Inline: False
```
**Symbols:**

```
ffffffff8107a050-ffffffff8107a06f: x86_msi_msg_get_destid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 x86_msi_msg_get_destid(struct msi_msg *msg, bool extid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81088df0)
Location: arch/x86/kernel/apic/apic.c:2552
Inline: False
```
**Symbols:**

```
ffffffff81088df0-ffffffff81088e19: x86_msi_msg_get_destid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 x86_msi_msg_get_destid(struct msi_msg *msg, bool extid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109ca50)
Location: arch/x86/kernel/apic/apic.c:2586
Inline: False
```
**Symbols:**

```
ffffffff8109ca50-ffffffff8109ca79: x86_msi_msg_get_destid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 x86_msi_msg_get_destid(struct msi_msg *msg, bool extid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109f970)
Location: arch/x86/kernel/apic/apic.c:2603
Inline: False
```
**Symbols:**

```
ffffffff8109f970-ffffffff8109f999: x86_msi_msg_get_destid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 x86_msi_msg_get_destid(struct msi_msg *msg, bool extid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a6d30)
Location: arch/x86/kernel/apic/apic.c:2487
Inline: False
```
**Symbols:**

```
ffffffff810a6d30-ffffffff810a6d59: x86_msi_msg_get_destid (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
