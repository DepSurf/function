# Function: <code>trace_module_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114b6e0)
Location: kernel/trace/trace.c:6930
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811606f0)
Location: kernel/trace/trace_events.c:2509
Inline: False
```
**Symbols:**

```
ffffffff8114b6e0-ffffffff8114b722: trace_module_notify (STB_LOCAL)
ffffffff811606f0-ffffffff811608b3: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811540f0)
Location: kernel/trace/trace.c:7337
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff8116ab80)
Location: kernel/trace/trace_events.c:2414
Inline: False
```
**Symbols:**

```
ffffffff811540f0-ffffffff81154132: trace_module_notify (STB_LOCAL)
ffffffff8116ab80-ffffffff8116ad3d: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115e370)
Location: kernel/trace/trace.c:7623
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81175f30)
Location: kernel/trace/trace_events.c:2383
Inline: False
```
**Symbols:**

```
ffffffff8115e370-ffffffff8115e3b2: trace_module_notify (STB_LOCAL)
ffffffff81175f30-ffffffff811760ed: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811612a0)
Location: kernel/trace/trace.c:7992
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81178f20)
Location: kernel/trace/trace_events.c:2423
Inline: False
```
**Symbols:**

```
ffffffff811612a0-ffffffff811612e2: trace_module_notify (STB_LOCAL)
ffffffff81178f20-ffffffff811790da: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116e720)
Location: kernel/trace/trace.c:8003
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81186620)
Location: kernel/trace/trace_events.c:2436
Inline: False
```
**Symbols:**

```
ffffffff8116e720-ffffffff8116e762: trace_module_notify (STB_LOCAL)
ffffffff81186620-ffffffff811867a3: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117d7a0)
Location: kernel/trace/trace.c:8104
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2436
Inline: False
```
**Symbols:**

```
ffffffff8117d7a0-ffffffff8117d7e2: trace_module_notify (STB_LOCAL)
ffffffff81195690-ffffffff81195805: trace_module_notify (STB_LOCAL)
ffffffff811965a9-ffffffff811965bf: trace_module_notify.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118b010)
Location: kernel/trace/trace.c:8178
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2437
Inline: False
```
**Symbols:**

```
ffffffff8118b010-ffffffff8118b052: trace_module_notify (STB_LOCAL)
ffffffff811a3630-ffffffff811a37a5: trace_module_notify (STB_LOCAL)
ffffffff811a46ea-ffffffff811a4700: trace_module_notify.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199030)
Location: kernel/trace/trace.c:8687
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2427
Inline: False
```
**Symbols:**

```
ffffffff81199030-ffffffff81199079: trace_module_notify (STB_LOCAL)
ffffffff811b1520-ffffffff811b1690: trace_module_notify (STB_LOCAL)
ffffffff811b2639-ffffffff811b264f: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a49b0)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
ffffffff811a49b0-ffffffff811a49f9: trace_module_notify (STB_LOCAL)
ffffffff811bcbc0-ffffffff811bcd30: trace_module_notify (STB_LOCAL)
ffffffff811bdc44-ffffffff811bdc5a: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811baeb0)
Location: kernel/trace/trace.c:9026
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2631
Inline: False
```
**Symbols:**

```
ffffffff811baeb0-ffffffff811baef9: trace_module_notify (STB_LOCAL)
ffffffff811d6100-ffffffff811d62d0: trace_module_notify (STB_LOCAL)
ffffffff811d741c-ffffffff811d7432: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b8a50)
Location: kernel/trace/trace.c:9159
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2647
Inline: False
```
**Symbols:**

```
ffffffff811b8a50-ffffffff811b8a9f: trace_module_notify (STB_LOCAL)
ffffffff811d33d0-ffffffff811d35f2: trace_module_notify (STB_LOCAL)
ffffffff81be61be-ffffffff81be61d4: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9300)
Location: kernel/trace/trace.c:9498
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2858
Inline: False
```
**Symbols:**

```
ffffffff811b9300-ffffffff811b934f: trace_module_notify (STB_LOCAL)
ffffffff811d46a0-ffffffff811d4895: trace_module_notify (STB_LOCAL)
ffffffff81bd7e48-ffffffff81bd7e5e: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e36c0)
Location: kernel/trace/trace.c:9660
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2875
Inline: False
```
**Symbols:**

```
ffffffff811e36c0-ffffffff811e370f: trace_module_notify (STB_LOCAL)
ffffffff81201570-ffffffff81201706: trace_module_notify (STB_LOCAL)
ffffffff81cb64a2-ffffffff81cb64b7: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121aa30)
Location: kernel/trace/trace.c:9696
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2978
Inline: False
```
**Symbols:**

```
ffffffff8121aa30-ffffffff8121aa93: trace_module_notify (STB_LOCAL)
ffffffff8123c750-ffffffff8123c970: trace_module_notify (STB_LOCAL)
ffffffff81e6741a-ffffffff81e6742f: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812647a0)
Location: kernel/trace/trace.c:9789
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81289de0)
Location: kernel/trace/trace_events.c:3069
Inline: False
```
**Symbols:**

```
ffffffff812647a0-ffffffff81264803: trace_module_notify (STB_LOCAL)
ffffffff81289de0-ffffffff8128a015: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127b7d0)
Location: kernel/trace/trace.c:9954
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff812a6a90)
Location: kernel/trace/trace_events.c:3063
Inline: False
```
**Symbols:**

```
ffffffff8127b7d0-ffffffff8127b833: trace_module_notify (STB_LOCAL)
ffffffff812a6a90-ffffffff812a6cba: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812963c0)
Location: kernel/trace/trace.c:10149
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff812c3490)
Location: kernel/trace/trace_events.c:3255
Inline: False
```
**Symbols:**

```
ffffffff812963c0-ffffffff81296423: trace_module_notify (STB_LOCAL)
ffffffff812c3490-ffffffff812c36ba: trace_module_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021f8f8)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (ffff80001023bec8)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
ffff80001021f8f8-ffff80001021f950: trace_module_notify (STB_LOCAL)
ffff80001023bec8-ffff80001023c08c: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045da6c)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (c0477770)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
c045da6c-c045dacc: trace_module_notify (STB_LOCAL)
c0477770-c0477904: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a3440)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (c0000000002ca660)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
c0000000002a3440-c0000000002a34c0: trace_module_notify (STB_LOCAL)
c0000000002ca660-c0000000002ca904: trace_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017c4b8)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffe0001920be)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
ffffffe00017c4b8-ffffffe00017c502: trace_module_notify (STB_LOCAL)
ffffffe0001920be-ffffffe00019224e: trace_module_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119cfd0)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
ffffffff8119cfd0-ffffffff8119d019: trace_module_notify (STB_LOCAL)
ffffffff811b51e0-ffffffff811b5350: trace_module_notify (STB_LOCAL)
ffffffff811b6264-ffffffff811b627a: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190030)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
ffffffff81190030-ffffffff81190079: trace_module_notify (STB_LOCAL)
ffffffff811a7fe0-ffffffff811a8150: trace_module_notify (STB_LOCAL)
ffffffff811a9064-ffffffff811a907a: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ada0)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
ffffffff8119ada0-ffffffff8119ade9: trace_module_notify (STB_LOCAL)
ffffffff811b2fb0-ffffffff811b3120: trace_module_notify (STB_LOCAL)
ffffffff811b4034-ffffffff811b404a: trace_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
int trace_module_notify(struct notifier_block *self, long unsigned int val, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8a40)
Location: kernel/trace/trace.c:8743
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2426
Inline: False
```
**Symbols:**

```
ffffffff811a8a40-ffffffff811a8a89: trace_module_notify (STB_LOCAL)
ffffffff811c1050-ffffffff811c11c0: trace_module_notify (STB_LOCAL)
ffffffff811c20d4-ffffffff811c20ea: trace_module_notify.cold (STB_LOCAL)
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
