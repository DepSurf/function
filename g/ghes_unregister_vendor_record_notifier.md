# Function: <code>ghes_unregister_vendor_record_notifier</code>

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
void ghes_unregister_vendor_record_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8170de10)
Location: drivers/acpi/apei/ghes.c:534
Inline: False
```
**Symbols:**

```
ffffffff8170de10-ffffffff8170de2a: ghes_unregister_vendor_record_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ghes_unregister_vendor_record_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816ef5b0)
Location: drivers/acpi/apei/ghes.c:583
Inline: False
```
**Symbols:**

```
ffffffff816ef5b0-ffffffff816ef5ca: ghes_unregister_vendor_record_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ghes_unregister_vendor_record_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81769610)
Location: drivers/acpi/apei/ghes.c:583
Inline: False
```
**Symbols:**

```
ffffffff81769610-ffffffff8176962a: ghes_unregister_vendor_record_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ghes_unregister_vendor_record_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8189e4f0)
Location: drivers/acpi/apei/ghes.c:583
Inline: False
```
**Symbols:**

```
ffffffff8189e4f0-ffffffff8189e514: ghes_unregister_vendor_record_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ghes_unregister_vendor_record_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e7580)
Location: drivers/acpi/apei/ghes.c:599
Inline: False
```
**Symbols:**

```
ffffffff819e7580-ffffffff819e75a4: ghes_unregister_vendor_record_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ghes_unregister_vendor_record_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a2fc90)
Location: drivers/acpi/apei/ghes.c:597
Inline: False
```
**Symbols:**

```
ffffffff81a2fc90-ffffffff81a2fcb4: ghes_unregister_vendor_record_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ghes_unregister_vendor_record_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7b010)
Location: drivers/acpi/apei/ghes.c:634
Inline: False
```
**Symbols:**

```
ffffffff81a7b010-ffffffff81a7b034: ghes_unregister_vendor_record_notifier (STB_GLOBAL)
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
