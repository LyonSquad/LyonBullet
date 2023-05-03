# LyonBullet
Lyon Bullet

        <StackPanel Grid.Row="0">
            <TextBlock
                   FontSize="14" 
                   TextWrapping="Wrap" 
                   Foreground="{DynamicResource ForegroundMain}">
                <Italic>LyonBullet</Italic> is a webtesting suite that can be used for <Bold>scraping</Bold> and <Bold>parsing</Bold> data, automated <Bold>pentesting</Bold>, selenium <Bold>unit testing</Bold> and much more..
                <LineBreak/><LineBreak/>
                <Span Foreground="{DynamicResource ForegroundBad}"><Bold>IT IS ILLEGAL</Bold> to use this program to perform (D)DoS or credential stuffing attacks on sites you don't own!</Span>
                <LineBreak/><LineBreak/>
                Make a Donation:
                <LineBreak/><LineBreak/>
                <Span Foreground="{DynamicResource ForegroundGood}"> BTC: 1GtFGsFqjnYiXKPwVXgxXRoR3qeoD2286L</Span>
				<TextBlock><Hyperlink NavigateUri="https://nowpayments.io/donation/yashvirgaming">CLICK HERE TO DONATE CRYPTO</Hyperlink></TextBlock>
                <LineBreak/>
                <Span Foreground="{DynamicResource ForegroundGood}"> LTC: LRwW5M2o1YSr9QT7biH28SYapcHsC5wUjR</Span>
                <LineBreak/><LineBreak/>
                <Span Foreground="{DynamicResource ForegroundGood}">This software is <Italic>Open Source</Italic> and licensed under the MIT license. Please visit the <Bold>repository</Bold> using the button below.</Span>				
				<TextBlock><Hyperlink NavigateUri="https://t.me/imakeconfigs">JOIN OFFICIAL TELEGRAM CHANNEL</Hyperlink></TextBlock>
            </TextBlock>
        </StackPanel>

        <StackPanel Orientation="Horizontal" Grid.Row="2">
            <Button x:Name="repoButton" Click="repoButton_Click" Margin="0 5">
                <StackPanel Orientation="Horizontal">
                    <Image Source="/Images/Icons/git.png" Width="20" />
                    <TextBlock VerticalAlignment="Center" Margin="5 0">Repository</TextBlock>
                </StackPanel>
            </Button>
            <Button x:Name="docuButton" Click="docuButton_Click" Margin="0 5">
                <StackPanel Orientation="Horizontal">
                    <Image Source="/Images/Icons/book.png" Width="20" />
                    <TextBlock VerticalAlignment="Center" Margin="5 0">Usage Guide</TextBlock>
                </StackPanel>
            </Button>
        </StackPanel>
    </Grid>
</Page>
