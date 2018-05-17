# 2016-Democratic-Presidential-Primary
Using US Census Data on County Demographics we can explore trends between county characteristics and
how strongly the county voted for one candidate versus the other. It is important to note that we are
specifically looking at the population voting in the Democratic Primaries and as such this is not representative
of the general public or even left leaning Americans as a whole. However it does give a look into the most
energetic voting base of the Democratic Party. This population does ultimately decide who will be the
Democratic Presidential Candidate, so they are still a worthwhile population to study.

# Methodology
For this study we will be using demographic characteristics of a county to fit a mutilinear regression to
predict how strongly a county voted for Hillary Clinton or Bernie Sanders. Our response variable will be the difference in
percentage of votes each candidate received. We shall call this variable Outcome and it is derived from the
following formula.
Outcome = Clinton % - Sanders %
Thus any positive value for Outcome indicates a Clinton win for that county and any negative value for
Outcome indicates a Sanders win for that county. This is a common response variable modeling in political
sciences and news casting and will help us reflect the more dynamic relationship between county demographics
and preferred candidate. This sort of coding is traditionally referred to as a point difference and we will
continue this terminology. So if we say Clinton is favored by 2 points this equates to her getting an extra 1%
of the vote over Sanders. Thus
Outcome / 2 = Precentage of Vote above 50
where any positive value is the percentage above 50% for Clinton and any negative value is the percentage
above 50% for Sanders.
