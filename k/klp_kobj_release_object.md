# Function: <code>klp_kobj_release_object</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:683
Inline: False
```
**Symbols:**

```
ffffffff810f0120-ffffffff810f012b: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff810f6cd0-ffffffff810f6cdb: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f7560)
Location: kernel/livepatch/core.c:539
Inline: True
```
**Symbols:**

```
ffffffff810f7560-ffffffff810f756b: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81101600)
Location: kernel/livepatch/core.c:553
Inline: True
```
**Symbols:**

```
ffffffff81101600-ffffffff8110160b: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81109a50)
Location: kernel/livepatch/core.c:612
Inline: True
```
**Symbols:**

```
ffffffff81109a50-ffffffff81109a5b: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81115220)
Location: kernel/livepatch/core.c:612
Inline: True
```
**Symbols:**

```
ffffffff81115220-ffffffff8111522b: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111f360)
Location: kernel/livepatch/core.c:545
Inline: False
```
**Symbols:**

```
ffffffff8111f360-ffffffff8111f389: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112bab0)
Location: kernel/livepatch/core.c:545
Inline: False
```
**Symbols:**

```
ffffffff8112bab0-ffffffff8112bad9: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8113a1f0)
Location: kernel/livepatch/core.c:567
Inline: False
```
**Symbols:**

```
ffffffff8113a1f0-ffffffff8113a21c: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81134ce0)
Location: kernel/livepatch/core.c:567
Inline: False
```
**Symbols:**

```
ffffffff81134ce0-ffffffff81134d0c: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81135bb0)
Location: kernel/livepatch/core.c:566
Inline: False
```
**Symbols:**

```
ffffffff81135bb0-ffffffff81135bdc: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:566
Inline: False
```
**Symbols:**

```
ffffffff811587d0-ffffffff81158810: klp_kobj_release_object (STB_LOCAL)
ffffffff81caf9da-ffffffff81caf9ef: klp_kobj_release_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:566
Inline: False
```
**Symbols:**

```
ffffffff81181d10-ffffffff81181d60: klp_kobj_release_object (STB_LOCAL)
ffffffff81e60675-ffffffff81e6068a: klp_kobj_release_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:590
Inline: False
```
**Symbols:**

```
ffffffff811bc680-ffffffff811bc6d0: klp_kobj_release_object (STB_LOCAL)
ffffffff8205a467-ffffffff8205a47c: klp_kobj_release_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:605
Inline: False
```
**Symbols:**

```
ffffffff811cf010-ffffffff811cf060: klp_kobj_release_object (STB_LOCAL)
ffffffff820d8c95-ffffffff820d8caa: klp_kobj_release_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:605
Inline: False
```
**Symbols:**

```
ffffffff811e3bf0-ffffffff811e3c40: klp_kobj_release_object (STB_LOCAL)
ffffffff821b43ce-ffffffff821b43e3: klp_kobj_release_object.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001eef30)
Location: kernel/livepatch/core.c:545
Inline: False
```
**Symbols:**

```
c0000000001eef30-c0000000001eef90: klp_kobj_release_object (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81124090)
Location: kernel/livepatch/core.c:545
Inline: False
```
**Symbols:**

```
ffffffff81124090-ffffffff811240b9: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81116af0)
Location: kernel/livepatch/core.c:545
Inline: False
```
**Symbols:**

```
ffffffff81116af0-ffffffff81116b19: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81121f80)
Location: kernel/livepatch/core.c:545
Inline: False
```
**Symbols:**

```
ffffffff81121f80-ffffffff81121fa9: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_kobj_release_object(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112e590)
Location: kernel/livepatch/core.c:545
Inline: False
```
**Symbols:**

```
ffffffff8112e590-ffffffff8112e5b9: klp_kobj_release_object (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
