# fairstaking1kv

现状：目前1kv共约158个valid node（ https://kusama.w3f.community/invalid） ，质押比例仅为33%左右（），也就是说，大约有70%的节点实际无法获取到有效的收益去支撑节点的运行。但是我们也有理由猜测，web3应该无法提供足够的staking让所有节点都进入active set，因为目前ksm最小的staking必须到5000以上才能成功入选。5000*158大约总公需要79万，这个数字对于web3来说，有些太庞大了。因为，我们认为需要引入新的机制来解决1kv中大多数节点质押不足的问题。


目标：解决目前1kv中大部分节点难以获取web3的直接支持，从而不能进入1KV Active Set的问题。


解决问题的思路：DeFI。我们创建Defi，接受来自任何ksm用户的自动委托，通过委托向1kv中的inactive set提供一键质押功能（随机选择任意4个inactive set进行质押），在功能上该质押等同于用户直接选择节点质押，所以在任意时刻用户均可以撤回质押或者再次选择手动质押。

意义：通过Defi，解决1kv中流动性不足的问题，通过吸纳自有用户的为1kv增加流动性，提高1kv用户的质押比例。

需要提供的支持：1）希望能在polkadot app中提供fairstaking1kv入口。
               2）国库支持，500ksm
