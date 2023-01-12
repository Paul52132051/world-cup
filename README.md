# world-cup
// Assuming there are 32 teams competing in the World Cup

double[] team_odds = {0.1, 0.2, 0.05, 0.03, ...}; // the odds of each team winning
double total_odds = 0;

for (int i = 0; i < team_odds.length; i++) {
    total_odds += team_odds[i];
}

for (int i = 0; i < team_odds.length; i++) {
    double chance_of_winning = team_odds[i] / total_odds;
    System.out.println("The chance of team " + i + " winning the World Cup is: " + chance_of_winning);
}
