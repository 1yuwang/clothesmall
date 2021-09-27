<template>
  <div class="wrapper">
    <ul class="">
    <li>商品展示1</li>
    <li>商品展示2</li>
    <li>商品展示3</li>
    <li>商品展示4</li>
    <li>商品展示5</li>
    <li>商品展示6</li>
    <li>商品展示7</li>
    <li>商品展示8</li>
    <li>商品展示9</li>
    <li>商品展示10</li>
    <li>商品展示11</li>
    <li>商品展示12</li>
    <li>商品展示13</li>
    <li>商品展示14</li>
    <li>商品展示15</li>
    <li>商品展示16</li>
    <li>商品展示17</li>
    <li>商品展示18</li>
    <li>商品展示19</li>
    <li>商品展示20</li>
    <li>商品展示21</li>
    <li>商品展示22</li>
    <li>商品展示23</li>
    <li>商品展示24</li>
    <li>商品展示25</li>
    <li>商品展示26</li>
    <li>商品展示27</li>
    <li>商品展示28</li>
    <li>商品展示29</li>
    <li>商品展示30</li>
    <li>商品展示31</li>
    <li>商品展示32</li>
    <li>商品展示33</li>
    <li>商品展示34</li>
    <li>商品展示35</li>
    <li>商品展示36</li>
    <li>商品展示37</li>
    <li>商品展示38</li>
    <li>商品展示39</li>
    <li>商品展示40</li>
    <li>商品展示41</li>
    <li>商品展示42</li>
    <li>商品展示43</li>
    <li>商品展示44</li>
    <li>商品展示45</li>
    <li>商品展示46</li>
    <li>商品展示47</li>
    <li>商品展示48</li>
    <li>商品展示49</li>
    <li>商品展示50</li>
    <li>商品展示51</li>
    <li>商品展示52</li>
    <li>商品展示53</li>
    <li>商品展示54</li>
    <li>商品展示55</li>
    <li>商品展示56</li>
    <li>商品展示57</li>
    <li>商品展示58</li>
    <li>商品展示59</li>
    <li>商品展示60</li>
    <li>商品展示61</li>
    <li>商品展示62</li>
    <li>商品展示63</li>
    <li>商品展示64</li>
    <li>商品展示65</li>
    <li>商品展示66</li>
    <li>商品展示67</li>
    <li>商品展示68</li>
    <li>商品展示69</li>
    <li>商品展示70</li>
    <li>商品展示71</li>
    <li>商品展示72</li>
    <li>商品展示73</li>
    <li>商品展示74</li>
    <li>商品展示75</li>
    <li>商品展示76</li>
    <li>商品展示77</li>
    <li>商品展示78</li>
    <li>商品展示79</li>
    <li>商品展示80</li>
    <li>商品展示81</li>
    <li>商品展示82</li>
    <li>商品展示83</li>
    <li>商品展示84</li>
    <li>商品展示85</li>
    <li>商品展示86</li>
    <li>商品展示87</li>
    <li>商品展示88</li>
    <li>商品展示89</li>
    <li>商品展示90</li>
    <li>商品展示91</li>
    <li>商品展示92</li>
    <li>商品展示93</li>
    <li>商品展示94</li>
    <li>商品展示95</li>
    <li>商品展示96</li>
    <li>商品展示97</li>
    <li>商品展示98</li>
    <li>商品展示99</li>
    <li>商品展示100</li>
  </ul>
  </div>
</template>

<script>

  import BScroll from 'better-scroll'
  export default {
    name: "Category",
    data() {
      return {
        scroll: null
      }
    },
  mounted() {
    this.scroll = new BScroll('.wrapper', {
      probeType: 3
    })

    this.scroll.on('scroll', (position) => {
      console.log(position);
    })
  }
  }  
</script>

<style>
  .wrapper {
    height: 150px;
    background-color: red;
  }
</style>
