# Function: <code>srcu_module_notify</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118700)
Location: kernel/rcu/srcutree.c:1342
Inline: True
```
**Symbols:**

```
ffffffff81118700-ffffffff81118797: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124ad0)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
ffffffff81124ad0-ffffffff81124b67: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132230)
Location: kernel/rcu/srcutree.c:1359
Inline: False
```
**Symbols:**

```
ffffffff81132230-ffffffff811322c7: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112da00)
Location: kernel/rcu/srcutree.c:1348
Inline: False
```
**Symbols:**

```
ffffffff8112da00-ffffffff8112da97: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e030)
Location: kernel/rcu/srcutree.c:1436
Inline: False
```
**Symbols:**

```
ffffffff8112e030-ffffffff8112e0c7: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114f4e0)
Location: kernel/rcu/srcutree.c:1435
Inline: False
```
**Symbols:**

```
ffffffff8114f4e0-ffffffff8114f577: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811767f0)
Location: kernel/rcu/srcutree.c:1790
Inline: False
```
**Symbols:**

```
ffffffff811767f0-ffffffff81176898: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae230)
Location: kernel/rcu/srcutree.c:1859
Inline: False
```
**Symbols:**

```
ffffffff811ae230-ffffffff811ae2d8: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1946
Inline: False
```
**Symbols:**

```
ffffffff811bf8a0-ffffffff811bf9b9: srcu_module_notify (STB_LOCAL)
ffffffff820d86d0-ffffffff820d86e5: srcu_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1972
Inline: False
```
**Symbols:**

```
ffffffff811cfd10-ffffffff811cfe29: srcu_module_notify (STB_LOCAL)
ffffffff821b399a-ffffffff821b39af: srcu_module_notify.cold (STB_LOCAL)
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
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff800010189fc0)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
ffff800010189fc0-ffff80001018a084: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8a5c)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
c03d8a5c-c03d8b34: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e48f0)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
c0000000001e48f0-c0000000001e4a40: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f140)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
ffffffe00011f140-ffffffe00011f1da: srcu_module_notify (STB_LOCAL)
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
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d0b0)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
ffffffff8111d0b0-ffffffff8111d147: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e170)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
ffffffff8110e170-ffffffff8110e207: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111afa0)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
ffffffff8111afa0-ffffffff8111b037: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int srcu_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126880)
Location: kernel/rcu/srcutree.c:1344
Inline: True
```
**Symbols:**

```
ffffffff81126880-ffffffff81126917: srcu_module_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
