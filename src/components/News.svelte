<script>
 import Card, {
    Content,
     PrimaryAction,
    Media,
    MediaContent,
    Actions,
    ActionButtons,
    ActionIcons,
  } from '@smui/card';
  import Button, { Label } from '@smui/button';
  import IconButton, { Icon } from '@smui/icon-button';
  import Paper, {Title}  from '@smui/paper/dist';

const popularNews = [
    {
        date: '24.02.2022',
        name: 'Lorem impsum',
        img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/news/02/anti_war_hand.png',
        instagram: '',
        shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
    }, 
    {
        date: '24.02.2022',
        name: 'Lorem impsum',
        img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/news/02/pl_ua.png',
        instagram: '',
        shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
    },
        {
        date: '24.02.2022',
        name: 'Lorem impsum',
        img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/news/02/spiymav.png',
        instagram: '',
        shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
    },
        {
        date: '24.02.2022',
        name: 'Lorem impsum',
        img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/news/02/we_love_you.png',
        instagram: '',
        shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
    },
];

const fullArrayNews = [
      {
         date: '24.02.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/1.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '25.02.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/2.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '26.02.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/3.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '27.02.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/4.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '28.02.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/5.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '01.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/6.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '02.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/7.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '03.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/8.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '04.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/9.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '05.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/10.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '06.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/11.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '07.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/12.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '08.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/13.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '09.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/14.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '10.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/15.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '11.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/16.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '12.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/17.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '13.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/18.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
       {
         date: '14.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/19.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '15.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/20.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '16.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/21.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '17.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/22.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '18.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/23.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '19.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/24.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '20.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/25.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '21.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/26.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '22.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/27.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '23.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/28.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '24.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/29.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '25.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/30.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '26.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/31.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
     {
         date: '27.03.2022',
         name: 'Lorem impsum',
         img: 'https://raw.githubusercontent.com/oleg-darkdev/no-war/master/static/img/bg/days/32.png',
         shortDescription: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
         popularNews,
     },
    
 ];


let newsArray = fullArrayNews.slice(0, 5);
</script>

<section style="width: 100%; height: auto; ">
  <div style="background-color: #F2DD31; display: flex; justify-content: center; ">
    <Paper color="primary" style="width: auto; max-width: 1080px; margin: -30px 0 -30px 0; background-color: #1A1A1A;  max-width: 1200px;" >
        <Content style="display: flex; justify-content: center; flex-direction: column; ">
        {#each newsArray as news}
            <Card style="width: 1024px; min-width:400px; margin: 25px 0;">
                <Content style=" background-image: url({news.img}); height: 315px; background-size: contain; background-repeat: no-repeat; ">
                </Content>
                <Actions fullBleed>
                <Button on:click={() => news.showNewsThisDay = !news.showNewsThisDay}>
                    <Label>{news.date} - {news.shortDescription} </Label>
                    <i class="material-icons" aria-hidden="true">arrow_forward</i>
                </Button>
                </Actions>
            </Card>
            {#if news.showNewsThisDay}
            <div class="top-news-wrap">
              {#each news.popularNews as topNews}
                <Card style="width: 350px; height: 350px; margin: 5px;">
                  <PrimaryAction on:click={() => topNews.showDescription = !topNews.shortDescription}>
                    <Media class="card-media-square" style="background-image: url({topNews.img});" aspectRatio="square">
                         <div style="color: #fff; position: absolute; bottom: 16px; left: 16px;">
                          {#if topNews.showDescription }
                            <h2 class="mdc-typography--headline6" style="margin: 0;">
                              {topNews.name}
                            </h2>
                            <h3 class="mdc-typography--subtitle2" style="margin: 0;">
                              {topNews.shortDescription}
                            </h3>
                          {/if}
                        </div>
                    </Media>
                    </PrimaryAction>
                  </Card>
                {/each}
            </div>
            {/if}
        {/each}
        <Card style="width: 350px;  margin: 10px 0 25px 0;">
            <PrimaryAction style="height: 100px; background-color: #F2DD31; " on:click={() => newsArray = fullArrayNews} padded>
                <h3 style="font: 54px 'impact'; margin: 0; text-align:center;">Show all news</h3>
            </PrimaryAction>
        </Card>
      </Content>
    </Paper>
  </div>
</section>

<style>
    .top-news-wrap {
      max-width: 1080px;
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      justify-content: space-between;
    }
</style>