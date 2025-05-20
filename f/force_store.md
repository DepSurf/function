# Function: <code>force_store</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8110a150)
Location: kernel/livepatch/core.c:557
Inline: True
```
**Symbols:**

```
ffffffff8110a150-ffffffff8110a1f0: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81115920)
Location: kernel/livepatch/core.c:557
Inline: True
```
**Symbols:**

```
ffffffff81115920-ffffffff811159c0: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111f5c0)
Location: kernel/livepatch/core.c:373
Inline: True
```
**Symbols:**

```
ffffffff8111f5c0-ffffffff8111f660: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112bd10)
Location: kernel/livepatch/core.c:373
Inline: True
```
**Symbols:**

```
ffffffff8112bd10-ffffffff8112bdb0: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8113a400)
Location: kernel/livepatch/core.c:395
Inline: True
```
**Symbols:**

```
ffffffff8113a400-ffffffff8113a4a0: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d3240)
Location: kernel/reboot.c:674
Inline: False
```
```
In kernel/livepatch/core.c (ffffffff81134ef0)
Location: kernel/livepatch/core.c:395
Inline: True
```
**Symbols:**

```
ffffffff810d3240-ffffffff810d32c9: force_store (STB_LOCAL)
ffffffff81134ef0-ffffffff81134f90: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d4f30)
Location: kernel/reboot.c:674
Inline: False
```
```
In kernel/livepatch/core.c (ffffffff81135d70)
Location: kernel/livepatch/core.c:394
Inline: True
```
**Symbols:**

```
ffffffff810d4f30-ffffffff810d4fb9: force_store (STB_LOCAL)
ffffffff81135d70-ffffffff81135e10: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:753
Inline: False
```
```
In kernel/livepatch/core.c (ffffffff81158959)
Location: kernel/livepatch/core.c:394
Inline: True
```
**Symbols:**

```
ffffffff810e8120-ffffffff810e81b9: force_store (STB_LOCAL)
ffffffff81ca5719-ffffffff81ca572d: force_store.cold (STB_LOCAL)
ffffffff811588f0-ffffffff811589a3: force_store (STB_LOCAL)
ffffffff81cafa04-ffffffff81cafa19: force_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:1125
Inline: False
```
```
In kernel/livepatch/core.c (ffffffff81181e29)
Location: kernel/livepatch/core.c:394
Inline: True
```
**Symbols:**

```
ffffffff81102550-ffffffff811025f5: force_store (STB_LOCAL)
ffffffff81e54fbc-ffffffff81e54fd0: force_store.cold (STB_LOCAL)
ffffffff81181db0-ffffffff81181e73: force_store (STB_LOCAL)
ffffffff81e6069f-ffffffff81e606b4: force_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:1142
Inline: False
```
```
In kernel/livepatch/core.c (ffffffff811bc7b9)
Location: kernel/livepatch/core.c:402
Inline: True
```
**Symbols:**

```
ffffffff81127890-ffffffff81127935: force_store (STB_LOCAL)
ffffffff8205683f-ffffffff82056853: force_store.cold (STB_LOCAL)
ffffffff811bc740-ffffffff811bc803: force_store (STB_LOCAL)
ffffffff8205a491-ffffffff8205a4a6: force_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:1142
Inline: False
```
```
In kernel/livepatch/core.c (ffffffff811cf149)
Location: kernel/livepatch/core.c:417
Inline: True
```
**Symbols:**

```
ffffffff81134d30-ffffffff81134dd5: force_store (STB_LOCAL)
ffffffff820d4eae-ffffffff820d4ec2: force_store.cold (STB_LOCAL)
ffffffff811cf0d0-ffffffff811cf193: force_store (STB_LOCAL)
ffffffff820d8cbf-ffffffff820d8cd4: force_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:1165
Inline: False
```
```
In kernel/livepatch/core.c (ffffffff811e3d29)
Location: kernel/livepatch/core.c:417
Inline: True
```
**Symbols:**

```
ffffffff8113fd20-ffffffff8113fdc5: force_store (STB_LOCAL)
ffffffff821afd95-ffffffff821afda9: force_store.cold (STB_LOCAL)
ffffffff811e3cb0-ffffffff811e3d73: force_store (STB_LOCAL)
ffffffff821b43f8-ffffffff821b440d: force_store.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001ef5c0)
Location: kernel/livepatch/core.c:373
Inline: True
```
**Symbols:**

```
c0000000001ef5c0-c0000000001ef6c0: force_store (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811242f0)
Location: kernel/livepatch/core.c:373
Inline: True
```
**Symbols:**

```
ffffffff811242f0-ffffffff81124390: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81116d50)
Location: kernel/livepatch/core.c:373
Inline: True
```
**Symbols:**

```
ffffffff81116d50-ffffffff81116df0: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811221e0)
Location: kernel/livepatch/core.c:373
Inline: True
```
**Symbols:**

```
ffffffff811221e0-ffffffff81122280: force_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t force_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112e7f0)
Location: kernel/livepatch/core.c:373
Inline: True
```
**Symbols:**

```
ffffffff8112e7f0-ffffffff8112e890: force_store (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
