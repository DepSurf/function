# Function: <code>devm_unregister_reboot_notifier</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810af0e0)
Location: kernel/reboot.c:107
Inline: True
```
**Symbols:**

```
ffffffff810af0e0-ffffffff810af102: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b5f20)
Location: kernel/reboot.c:107
Inline: True
```
**Symbols:**

```
ffffffff810b5f20-ffffffff810b5f42: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810bf1b0)
Location: kernel/reboot.c:108
Inline: True
```
**Symbols:**

```
ffffffff810bf1b0-ffffffff810bf1d2: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810c57d5)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810c52c0-ffffffff810c52e2: devm_unregister_reboot_notifier (STB_LOCAL)
ffffffff810c57d5-ffffffff810c57e8: devm_unregister_reboot_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810ce3c0)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810ce3c0-ffffffff810ce3e2: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d80d0)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810d80d0-ffffffff810d80f2: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d32d0)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810d32d0-ffffffff810d32f2: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d4fc0)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810d4fc0-ffffffff810d4fe2: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810e7db0)
Location: kernel/reboot.c:111
Inline: False
```
**Symbols:**

```
ffffffff810e7db0-ffffffff810e7dd2: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81102150)
Location: kernel/reboot.c:120
Inline: False
```
**Symbols:**

```
ffffffff81102150-ffffffff81102186: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811273f0)
Location: kernel/reboot.c:120
Inline: False
```
**Symbols:**

```
ffffffff811273f0-ffffffff81127426: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81134890)
Location: kernel/reboot.c:120
Inline: False
```
**Symbols:**

```
ffffffff81134890-ffffffff811348c6: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8113f880)
Location: kernel/reboot.c:130
Inline: False
```
**Symbols:**

```
ffffffff8113f880-ffffffff8113f8b6: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffff80001012dde8)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffff80001012dde8-ffff80001012de30: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c037dc28)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
c037dc28-c037dc70: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c000000000176a00)
Location: kernel/reboot.c:110
Inline: False
```
**Symbols:**

```
c000000000176a00-c000000000176a50: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffe0000e1e6a)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffe0000e1e6a-ffffffe0000e1eaa: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c8740)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810c8740-ffffffff810c8762: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b6f60)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810b6f60-ffffffff810b6f82: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c7c70)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810c7c70-ffffffff810c7c92: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_reboot_notifier(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d0160)
Location: kernel/reboot.c:110
Inline: True
```
**Symbols:**

```
ffffffff810d0160-ffffffff810d0182: devm_unregister_reboot_notifier (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
