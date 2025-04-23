# mass_luminosity_relation.py

def luminosity(mass):
    """
    Calculate the luminosity of a star based on its mass.
    Luminosity (L) is proportional to mass (M) to the power of 3.5 (L ~ M^3.5).
    :param mass: Mass of the star in solar masses (M☉)
    :return: Luminosity of the star in solar luminosities (L☉)
    """
    return mass ** 3.5

# Example usage:
mass_of_star = 2  # Mass in solar masses (M☉)
lum = luminosity(mass_of_star)
print(f"The luminosity of a star with mass {mass_of_star} M☉ is {lum} L☉.")
