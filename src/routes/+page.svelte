<script>
    import Account from './../components/account.svelte';
    import Main from './../components/main.svelte';
	import Orderlist from './../components/orderlist.svelte';
    import Customer from "../components/customer.svelte";
    import Head from "../components/head.svelte";
    import Nav from "../components/nav.svelte";
  import Footer from '../components/footer.svelte';

    
</script>

<div class="relative h-auto bg-black">
    <Head/>
    <Main/>
    <Account/>
    <Nav/>
    <Customer/>
    <Orderlist/>
    <Footer/>
</div>
